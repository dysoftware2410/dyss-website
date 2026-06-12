# Form → Email setup (Google Apps Script)

The contact form posts to a small Google Apps Script "Web App" that emails every lead to contactus@automaze.co.il. No API key is needed — the script runs inside your Google Workspace account and uses its built-in mail service. One-time setup, ~5 minutes.

## 1. Create the script

1. Go to https://script.google.com while logged into the Google Workspace account.
2. Click **New project**, name it `Automaze Leads Mailer`.
3. Delete the default code and paste:

```javascript
const TO = 'contactus@automaze.co.il';

function doPost(e) {
  const p = (e && e.parameter) || {};
  const body =
    'שם: '    + (p.name  || '') + '\n' +
    'טלפון: ' + (p.phone || '') + '\n' +
    'עסק: '   + (p.biz   || '') + '\n' +
    'תחום: '  + (p.topic || '') + '\n' +
    'הודעה: ' + (p.msg   || '') + '\n\n' +
    '— נשלח מטופס האתר automaze.co.il';
  MailApp.sendEmail({
    to: TO,
    subject: 'ליד חדש מהאתר — ' + (p.name || 'ללא שם'),
    body: body
  });
  return ContentService
    .createTextOutput(JSON.stringify({ ok: true }))
    .setMimeType(ContentService.MimeType.JSON);
}
```

4. Save (Ctrl+S).

## 2. Deploy as Web App

1. Click **Deploy → New deployment**.
2. Gear icon → select type **Web app**.
3. Settings — these two matter:
   - **Execute as: Me** (the script sends mail from your account)
   - **Who has access: Anyone** (required so the website can post to it; the URL is unguessable and the script can only send mail to you)
4. Click **Deploy**, approve the authorization prompts (it will warn the app is unverified — that's normal for your own scripts; click Advanced → Go to project).
5. Copy the **Web app URL** (looks like `https://script.google.com/macros/s/AKfycb.../exec`).

## 3. Connect the website

In `index.html`, find this line in the script at the bottom:

```javascript
const FORM_ENDPOINT='';
```

Paste the URL between the quotes:

```javascript
const FORM_ENDPOINT='https://script.google.com/macros/s/AKfycb.../exec';
```

Commit and push. Until the URL is set, the form falls back to the old mailto behavior, so the site keeps working either way.

## 4. Test

Submit the form on the live site — the email should arrive within seconds. Check spam the first time.

## Notes

- The TO address must be a real mailbox. If contactus@automaze.co.il isn't set up in Workspace yet, put your personal address in the script temporarily — it's a one-line change, no redeploy of the site needed (but you must click Deploy → Manage deployments → edit → New version in Apps Script after changing script code).
- Quota: Workspace accounts can send ~1,500 emails/day via Apps Script (free Gmail: 100/day) — far more than enough.
- If you later want leads in a Google Sheet too, the same script can append a row — ask Claude to add it.
