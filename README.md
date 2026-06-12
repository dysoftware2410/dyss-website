# Automaze — אתר תדמית

אתר נחיתה סטטי (HTML/CSS/JS, ללא שלב build) לעסק Automaze: אוטומציה עסקית, סוכני AI, חיבור מערכות ובניית אתרים לעסקים בישראל.

## מבנה
- `index.html` — כל האתר (עברית, RTL, SEO מובנה: meta, Open Graph, JSON-LD).
- `logo.svg`, `favicon.*`, `apple-touch-icon.png`, `og-image.png` — נכסי מותג.
- `svc-*.webp` — תמונות לשירותים.
- `robots.txt`, `sitemap.xml` — SEO.
- `netlify.toml` — הגדרות פרסום ל-Netlify.

## הרצה מקומית
פותחים את `index.html` בדפדפן, או:
```bash
npx serve .
```

## פרסום ב-Netlify
האתר סטטי, ספריית הפרסום היא שורש הריפו (`publish = "."`). ראו הוראות בהמשך ההודעה בצ'אט.

## לפני העלייה — להחליף placeholders
- מספר טלפון: `054-449-7165`
- מספר וואטסאפ: `972544497165`
- דומיין: `automaze.co.il` (ב-`index.html`, `sitemap.xml`, `robots.txt`)
