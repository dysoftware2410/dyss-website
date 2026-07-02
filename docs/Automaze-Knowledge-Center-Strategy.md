# Automaze — Knowledge Center Strategy (Content & GEO Architecture)

**Prepared as a senior Content / SEO / GEO strategy document.**
Scope: the complete knowledge architecture for [automaze.co.il](https://automaze.co.il) — designed to make Automaze one of the most authoritative sources on **AI Automation, AI Business Solutions, and Digital Transformation** for both humans and LLMs (ChatGPT, Claude, Gemini, Perplexity).
Language of published pages: **Hebrew** (technical terms kept in English). This document is the blueprint — not the articles.

---

## 0. Strategic Principles

1. **Topic-cluster model.** Every category has ONE pillar page (broad, definitional, 3–5k words) surrounded by supporting articles that link up to the pillar and across to siblings. This concentrates topical authority.
2. **GEO-first writing.** Pages are structured so LLMs can extract and cite them: definition-first paragraphs, self-contained sections, comparison tables, FAQ blocks, glossaries, and Schema.org markup. We optimize for *being quoted*, not just ranked.
3. **Entity clarity.** The site should unambiguously define the entities Automaze is associated with (AI Automation, AI Agents, n8n, BPA, industries served). Consistent naming + glossary + schema teach models "Automaze = authority on X."
4. **Bilingual keyword reality.** Israeli searchers mix Hebrew + English ("בוט וואטסאפ", "n8n", "AI Agent"). Keep English technical terms; localize the explanations.
5. **Evidence & originality.** Differentiate with original frameworks, tools (calculators, assessments), templates, and real local (Israeli) context — the things competitors and generic AI agencies don't publish.
6. **Sustainable scale.** The architecture must support hundreds of pages over years without becoming a flat, unstructured blog.

---

## 1. Complete Site Hierarchy (Tree)

```
automaze.co.il/
├── / ................................ Homepage (commercial hub)
├── /about ........................... פרופיל חברה (entity: Organization)
├── /services/ ....................... Services hub (commercial)
│   ├── /services/ai-automation
│   ├── /services/ai-agents
│   ├── /services/business-process-automation
│   ├── /services/ai-workflows
│   ├── /services/custom-ai-solutions
│   ├── /services/integrations
│   ├── /services/website-development
│   ├── /services/internal-ai-assistants
│   └── /services/ai-consulting
│
├── /knowledge/ ...................... KNOWLEDGE CENTER (root hub)
│   ├── /knowledge/ai-fundamentals/          ▸ Pillar + supporting
│   ├── /knowledge/ai-automation/            ▸ Pillar (= /AIAutomations) + cluster
│   ├── /knowledge/ai-agents/                ▸ Pillar + cluster
│   ├── /knowledge/business-automation/      ▸ Pillar + cluster
│   ├── /knowledge/ai-workflows/             ▸ Pillar + cluster
│   ├── /knowledge/crm-automation/           ▸ Pillar + cluster
│   ├── /knowledge/sales-automation/         ▸ Pillar + cluster
│   ├── /knowledge/customer-support-automation/ ▸ Pillar + cluster
│   ├── /knowledge/marketing-automation/     ▸ Pillar + cluster
│   ├── /knowledge/integrations/             ▸ Pillar + cluster
│   ├── /knowledge/no-code-low-code/         ▸ Pillar + cluster
│   ├── /knowledge/custom-ai-solutions/      ▸ Pillar + cluster
│   ├── /knowledge/website-development/      ▸ Pillar + cluster
│   ├── /knowledge/data-and-integration/     ▸ Pillar + cluster
│   ├── /knowledge/security-privacy/         ▸ Pillar + cluster
│   ├── /knowledge/ai-governance/            ▸ Pillar + cluster
│   └── /knowledge/digital-transformation/   ▸ Pillar + cluster
│
├── /industries/ ..................... Industry landing pages (commercial + educational)
│   ├── /industries/real-estate
│   ├── /industries/ecommerce
│   ├── /industries/healthcare
│   ├── /industries/legal
│   ├── /industries/finance
│   ├── /industries/insurance
│   ├── /industries/professional-services
│   ├── /industries/construction
│   ├── /industries/manufacturing
│   ├── /industries/retail
│   ├── /industries/logistics
│   ├── /industries/education
│   ├── /industries/hospitality
│   └── /industries/government
│
├── /use-cases/ ...................... Problem/solution pages (mid-funnel)
│   ├── /use-cases/lead-automation
│   ├── /use-cases/customer-support
│   ├── /use-cases/document-processing
│   ├── /use-cases/invoice-automation
│   ├── /use-cases/appointment-scheduling
│   ├── /use-cases/whatsapp-bot
│   ├── /use-cases/report-automation
│   └── /use-cases/onboarding-automation
│
├── /compare/ ........................ Comparison pages (high-intent)
│   ├── /compare/make-vs-zapier-vs-n8n
│   ├── /compare/ai-agents-vs-chatbots
│   ├── /compare/ai-automation-vs-rpa
│   ├── /compare/build-vs-buy-vs-partner
│   └── /compare/off-the-shelf-vs-custom
│
├── /glossary/ ....................... Entity/definition pages (GEO gold)
│   ├── /glossary/ (index — DefinedTermSet)
│   └── /glossary/{term} × ~60 terms
│
├── /tools/ .......................... Interactive tools (link magnets + lead gen)
│   ├── /tools/roi-calculator
│   ├── /tools/ai-readiness-assessment
│   ├── /tools/automation-checklist
│   └── /tools/process-audit
│
├── /resources/ ...................... Downloadables (templates, playbooks, checklists)
├── /case-studies/ ................... Proof (case studies / results)
├── /faq/ ............................ Central FAQ hub (mirrors FAQPage schema)
└── /blog/ ........................... News, opinion, timely takes (feeds clusters)
```

> **Note on the existing site:** the current `/AIAutomations` pillar is the seed of `/knowledge/ai-automation/`. Existing blog posts (business-automation-guide, ai-agents-for-business, whatsapp-bot-for-business, make-vs-zapier-vs-n8n, processes-to-automate) map into the clusters below and should be re-linked accordingly rather than left as a flat blog.

---

## 2. Category Map (purpose of each category)

| Category | Purpose | Primary role |
|---|---|---|
| **AI Fundamentals** | Explain the base concepts (AI, ML, LLM, NLP) in business language. Feeds every other cluster. | Definitional / entity |
| **AI Automation** | The flagship topic. Broadest educational authority. | Cornerstone |
| **AI Agents** | Fast-growing, high-interest entity; agentic AI. | Cornerstone |
| **Business Process Automation** | Bridges traditional automation → AI. Captures BPA/RPA search demand. | Authority |
| **AI Workflows** | Practical "how automation is built" layer. | Supporting authority |
| **CRM Automation** | High commercial intent; connects to services. | Commercial-educational |
| **Sales Automation** | Lead capture, qualification, follow-up. | Commercial-educational |
| **Customer Support Automation** | Deflection, AI assistants, 24/7. | Commercial-educational |
| **Marketing Automation** | Content, nurture, campaigns. | Educational |
| **Integrations** | System-to-system, iPaaS, APIs. | Technical authority |
| **No-Code / Low-Code** | Make/Zapier/n8n audience. | Tool authority |
| **Custom AI Solutions** | Differentiator: bespoke builds beyond off-the-shelf. | Expertise signal |
| **Website Development** | Existing service; connects automation to web. | Commercial |
| **Data & Integration** | Data readiness, quality, pipelines — the hidden prerequisite. | Expertise signal |
| **Security & Privacy** | Trust, compliance, חוק הגנת הפרטיות. | Trust / E-E-A-T |
| **AI Governance** | Policies, guardrails, responsible AI. | Differentiator / trust |
| **Digital Transformation** | Umbrella narrative for executives. | Top-of-funnel authority |

---

## 3. Pillar Page Map

Each cluster is anchored by ONE pillar. Pillars are the pages we most want LLMs to cite and Google to rank for the head term.

| # | Pillar | Slug | Head keyword (HE/EN) | Status |
|---|---|---|---|---|
| P1 | AI Automation — מדריך מלא | `/AIAutomations` | AI Automation / אוטומציה מבוססת AI | ✅ Live |
| P2 | AI Agents — מדריך מלא | `/knowledge/ai-agents` | AI Agents / סוכני AI | Phase 1 |
| P3 | Business Process Automation | `/knowledge/business-automation` | אוטומציה עסקית / BPA | Phase 1 |
| P4 | AI Fundamentals for Business | `/knowledge/ai-fundamentals` | בינה מלאכותית לעסקים | Phase 2 |
| P5 | AI Workflows | `/knowledge/ai-workflows` | AI Workflows / תהליכי אוטומציה | Phase 2 |
| P6 | CRM Automation | `/knowledge/crm-automation` | אוטומציית CRM | Phase 2 |
| P7 | Sales Automation | `/knowledge/sales-automation` | אוטומציית מכירות | Phase 2 |
| P8 | Customer Support Automation | `/knowledge/customer-support-automation` | אוטומציית שירות לקוחות | Phase 2 |
| P9 | Integrations & iPaaS | `/knowledge/integrations` | אינטגרציות / חיבור מערכות | Phase 2 |
| P10 | No-Code / Low-Code Automation | `/knowledge/no-code-low-code` | No-Code אוטומציה | Phase 3 |
| P11 | Custom AI Solutions | `/knowledge/custom-ai-solutions` | פתרונות AI מותאמים | Phase 3 |
| P12 | Marketing Automation | `/knowledge/marketing-automation` | אוטומציית שיווק | Phase 3 |
| P13 | Website Development | `/knowledge/website-development` | בניית אתרים לעסק | Phase 3 |
| P14 | Data & Integration Readiness | `/knowledge/data-and-integration` | מוכנות נתונים | Phase 3 |
| P15 | Security & Privacy in AI | `/knowledge/security-privacy` | אבטחת מידע ופרטיות ב-AI | Phase 3 |
| P16 | AI Governance & Responsible AI | `/knowledge/ai-governance` | ממשל AI / AI אחראי | Phase 4 |
| P17 | Digital Transformation | `/knowledge/digital-transformation` | טרנספורמציה דיגיטלית | Phase 4 |

---

## 4. Topic Cluster Maps

Page-type legend: **PIL** pillar · **SUP** supporting article · **CMP** comparison · **BP** best practices · **GD** guide · **CL** checklist · **IND** industry · **GL** glossary · **FAQ** FAQ page · **CS** case study.

### 4.1 Cluster: AI Automation  (flagship — cornerstone)

| Type | Page Title (HE) | Slug | Search Intent | Audience | Primary KW | Secondary KW | Internal Links |
|---|---|---|---|---|---|---|---|
| PIL | AI Automation — המדריך המלא | `/AIAutomations` | Informational | Owners + decision makers | AI Automation | אוטומציה מבוססת AI, intelligent automation | → all SUP below, services, ROI tool |
| SUP | מה זה Intelligent Automation | `/knowledge/ai-automation/intelligent-automation` | Informational | Owners | intelligent automation | hyperautomation | ↑ PIL, ↔ BPA pillar |
| SUP | Hyperautomation — מדריך | `/knowledge/ai-automation/hyperautomation` | Informational | Ops leaders | hyperautomation | end-to-end automation | ↑ PIL |
| SUP | ROI של AI Automation — איך מחשבים | `/knowledge/ai-automation/roi` | Commercial-info | Owners/CFO | ROI אוטומציה | חיסכון אוטומציה | ↑ PIL, → ROI calculator |
| CMP | AI Automation מול RPA | `/compare/ai-automation-vs-rpa` | Commercial | Tech-curious | AI vs RPA | rule-based automation | ↑ PIL, ↔ BPA |
| BP | Best Practices ליישום AI Automation | `/knowledge/ai-automation/best-practices` | Informational | Implementers | AI automation best practices | human-in-the-loop | ↑ PIL |
| GD | איך להתחיל עם AI Automation | `/knowledge/ai-automation/getting-started` | How-to | Beginners | להתחיל אוטומציה AI | first automation | ↑ PIL, → readiness assessment |
| CL | צ'קליסט מוכנות ל-AI Automation | `/knowledge/ai-automation/readiness-checklist` | How-to | Owners | צ'קליסט אוטומציה | AI readiness | → assessment tool |
| FAQ | AI Automation — שאלות נפוצות | `/faq/ai-automation` | Informational | All | שאלות AI automation | — | ↑ PIL |
| GL | הגדרה: AI Automation | `/glossary/ai-automation` | Informational | All | הגדרת AI automation | — | ↑ PIL |

### 4.2 Cluster: AI Agents  (cornerstone)

| Type | Page Title (HE) | Slug | Search Intent | Audience | Primary KW | Secondary KW | Internal Links |
|---|---|---|---|---|---|---|---|
| PIL | AI Agents — המדריך המלא | `/knowledge/ai-agents` | Informational | Owners + tech | AI agents / סוכני AI | agentic AI, autonomous agents | → SUP, use-cases, /AIAutomations |
| SUP | Agentic AI — מה זה ולמה חשוב | `/knowledge/ai-agents/agentic-ai` | Informational | Decision makers | agentic AI | AI autonomy | ↑ PIL |
| SUP | Guardrails לסוכני AI | `/knowledge/ai-agents/guardrails` | Informational | Implementers | AI guardrails | safe AI agents | ↑ PIL, ↔ governance |
| SUP | Multi-agent systems — מדריך | `/knowledge/ai-agents/multi-agent` | Informational | Tech | multi-agent | agent orchestration | ↑ PIL |
| CMP | AI Agents מול Chatbots | `/compare/ai-agents-vs-chatbots` | Commercial | Owners | סוכן AI מול צ'אטבוט | chatbot vs agent | ↑ PIL, → WhatsApp use-case |
| BP | Best practices לפריסת AI Agent | `/knowledge/ai-agents/deployment-best-practices` | Informational | Implementers | deploy AI agent | agent monitoring | ↑ PIL |
| GD | איך בונים AI Agent לעסק | `/knowledge/ai-agents/build-guide` | How-to | Tech-curious | לבנות סוכן AI | agent tools | ↑ PIL |
| GL | הגדרה: AI Agent | `/glossary/ai-agent` | Informational | All | הגדרת סוכן AI | — | ↑ PIL |

### 4.3 Cluster: Business Process Automation (BPA)

| Type | Page Title (HE) | Slug | Search Intent | Audience | Primary KW | Secondary KW | Internal Links |
|---|---|---|---|---|---|---|---|
| PIL | אוטומציה עסקית — המדריך המלא | `/knowledge/business-automation` | Informational | Owners | אוטומציה עסקית / BPA | workflow automation | → SUP, /AIAutomations, services |
| SUP | 7 תהליכים שכדאי לאטמט | `/knowledge/business-automation/processes-to-automate` | Informational | Owners | תהליכים לאוטומציה | process automation | ↑ PIL (migrate existing post) |
| SUP | מיפוי תהליכים לפני אוטומציה | `/knowledge/business-automation/process-mapping` | How-to | Ops | מיפוי תהליכים | process discovery | ↑ PIL |
| CMP | אוטומציה: מוכנה מול מותאמת | `/compare/off-the-shelf-vs-custom` | Commercial | Owners | מערכת מוכנה מול מותאמת | build vs buy | ↑ PIL, ↔ custom AI |
| CL | צ'קליסט אוטומציה של תהליך | `/knowledge/business-automation/process-checklist` | How-to | Owners | צ'קליסט תהליך | — | → checklist resource |
| GL | הגדרה: Business Process Automation | `/glossary/business-process-automation` | Informational | All | הגדרת BPA | — | ↑ PIL |

### 4.4–4.17 Remaining Clusters (page inventory)

Each remaining pillar follows the same pattern (PIL + 4–8 SUP + 1–2 CMP + BP + GD + CL + GL + FAQ). Priority pages per cluster:

- **AI Fundamentals:** מה זה AI / ML / LLM / NLP / Generative AI (SUP+GL each) · "AI לעסקים — מדריך למתחילים" (PIL) · "AI מול Automation" (CMP).
- **AI Workflows:** PIL · "AI Workflow מול AI Agent" (CMP) · "אנטומיה של workflow" (SUP) · "trigger-action-logic" (GD) · error handling & monitoring (BP).
- **CRM Automation:** PIL · אוטומציה ב-HubSpot/Monday/Powerlink (SUP×3, local systems) · "CRM automation checklist" (CL) · lead scoring (SUP).
- **Sales Automation:** PIL · lead qualification (SUP) · follow-up sequences (GD) · speed-to-lead (SUP, cite stats) · WhatsApp lead bot (→ use-case).
- **Customer Support Automation:** PIL · AI assistant (SUP) · ticket deflection (SUP) · escalation design (BP) · knowledge base + RAG (GD).
- **Marketing Automation:** PIL · content generation (SUP) · nurture flows (GD) · AI SEO/GEO (SUP — original angle).
- **Integrations:** PIL · APIs vs iPaaS (CMP) · webhook basics (GD) · "מחברים את המערכות בישראל" (SUP, local systems: חשבונית ירוקה, Cardcom, Priority) · data mapping (BP).
- **No-Code/Low-Code:** PIL · Make guide · Zapier guide · n8n guide (GD×3) · Make vs Zapier vs n8n (CMP, migrate existing) · self-hosting n8n (GD).
- **Custom AI Solutions:** PIL · when custom beats off-the-shelf (SUP) · RAG systems (GD) · fine-tuning vs prompting vs RAG (CMP) · internal AI assistant (SUP).
- **Website Development:** PIL · SEO-ready sites (SUP) · site connected to automations (SUP) · landing pages that convert (GD).
- **Data & Integration Readiness:** PIL · data quality (SUP) · "why AI projects fail = data" (SUP, original) · data readiness checklist (CL).
- **Security & Privacy:** PIL · חוק הגנת הפרטיות ו-AI (SUP, local authority) · sending data to LLMs safely (BP) · self-hosted vs cloud AI (CMP).
- **AI Governance:** PIL · AI policy for SMBs (GD + template) · responsible AI (SUP) · human oversight (BP).
- **Digital Transformation:** PIL (exec narrative) · roadmap (GD) · change management (SUP) · SMB transformation in Israel (SUP, local).

---

## 5. Content Roadmap (Phased)

**Phase 1 — Critical (months 0–3).** Build the cornerstone pillars + their highest-intent comparison/FAQ pages, plus the two lead-gen tools. Rationale: these define the core entities (AI Automation, AI Agents, BPA), capture the highest commercial + informational demand, and are the pages LLMs are most likely to cite. Tools generate leads and backlinks immediately.
- Pillars: `/AIAutomations` ✅, AI Agents, Business Automation.
- Comparisons: AI Agents vs Chatbots, AI Automation vs RPA, Make vs Zapier vs n8n (migrate).
- Tools: ROI Calculator (exists on homepage — spin out as standalone `/tools/roi-calculator`), AI Readiness Assessment.
- Glossary seed: 15 core terms. Central FAQ hub.

**Phase 2 — High Priority (months 3–6).** Commercial-educational clusters that connect directly to services and revenue.
- Pillars: AI Fundamentals, AI Workflows, CRM Automation, Sales Automation, Customer Support Automation, Integrations.
- Use-cases: lead-automation, customer-support, document-processing, whatsapp-bot.
- First 3 industry pages (highest fit): Real Estate, E-commerce, Professional Services.
- Reason: converts the authority from Phase 1 into demand for services; use-cases are mid-funnel money pages.

**Phase 3 — Medium Priority (months 6–12).** Depth, differentiation, and long-tail coverage.
- Pillars: No-Code/Low-Code, Custom AI Solutions, Marketing Automation, Website Development, Data & Integration, Security & Privacy.
- Remaining comparisons, best-practice and guide pages, 40+ glossary terms, more use-cases.
- Industries 4–9. First case studies.
- Reason: broadens topical authority and long-tail capture once the core is indexed and trusted.

**Phase 4 — Nice to Have (months 12+).** Authority-cementing and executive content.
- Pillars: AI Governance, Digital Transformation.
- Templates, playbooks, policy generators, decision trees, prompt libraries.
- Remaining industries, thought-leadership blog, annual "State of AI Automation in Israel" report.
- Reason: these deepen E-E-A-T and originality but aren't required to start ranking/being cited.

---

## 6. Missing Content Opportunities (50+ ideas competitors miss)

**Interactive tools & calculators**
1. AI Automation ROI Calculator (exists — expand & standalone)
2. AI Readiness Assessment (scored quiz)
3. Process Automation Audit (which of my processes to automate?)
4. "Build vs Buy vs Partner" decision tool
5. Automation cost estimator (setup + run-cost)
6. Speed-to-lead impact calculator
7. Workflow complexity scorer
8. LLM cost estimator (tokens → ₪)
9. Manual-hours-saved tracker
10. AI use-case finder by industry (interactive)

**Assessments & frameworks (original IP)**
11. The Automaze Automation Maturity Model (5 levels)
12. AI-vs-traditional decision tree (visual)
13. Human-in-the-loop design framework
14. Automation prioritization matrix (impact × effort)
15. "Is this process ready to automate?" scorecard
16. Guardrails design checklist for agents
17. Data-readiness scorecard
18. Vendor lock-in risk assessment
19. AI project failure-modes framework
20. GEO/AEO readiness checklist for businesses

**Templates & downloadables**
21. Process-mapping template
22. Automation project brief template
23. AI policy template for SMBs (Hebrew)
24. Data processing agreement (DPA) checklist
25. Prompt library for business tasks (Hebrew prompts)
26. WhatsApp bot conversation-flow template
27. Lead-qualification question bank
28. SOP template for automated processes
29. Implementation playbook (step-by-step)
30. Change-management email templates
31. AI vendor evaluation scorecard
32. Automation ROI one-pager template
33. Incident/rollback runbook template
34. Handoff (AI → human) script templates
35. Monthly automation health-check template

**Original research & local angle**
36. "State of AI Automation in Israel" annual report
37. Benchmark: response-time by industry (Israel)
38. Cost of manual work calculator with Israeli wage data
39. Survey: SMB AI adoption in Israel
40. Israeli SaaS integration map (Priority, Powerlink, חשבונית ירוקה, Cardcom, Monday)
41. Hebrew AI prompt patterns that work
42. Privacy law (חוק הגנת הפרטיות) × AI practical guide

**Deep guides & comparisons rarely done well**
43. "Why AI projects fail (and it's usually data)"
44. RAG vs fine-tuning vs prompting — when to use each
45. Self-hosting n8n — full guide
46. Human oversight patterns for agents
47. Measuring AI quality (evals) for non-technical teams
48. Total cost of ownership: automation over 3 years
49. Migration guide: Zapier → Make/n8n
50. Multi-agent orchestration explained simply
51. AI automation for Hebrew-language operations (localization pitfalls)
52. "The 24/7 employee" economics deep-dive

**Formats**
53. Glossary as a browsable, schema-marked hub (60+ terms)
54. Video/GIF walkthroughs embedded in guides
55. Decision-tree diagrams (Mermaid) per major choice

---

## 7. Internal Linking Strategy

**Framework — link direction rules:**
- **Pillar → Supporting:** each pillar links down to every supporting article in its cluster (contextual + a cluster index block). Supporting articles link **up** to the pillar with exact-match anchor once, high in the body.
- **Supporting ↔ Supporting (siblings):** cross-link related articles within the same cluster (2–4 links).
- **Supporting → Case Study:** where a concept has proof, link to the matching case study.
- **Case Study → Service:** each case study links to the relevant `/services/*` page (conversion path).
- **Service → Educational:** service pages link back down to the pillar + top guides (keeps commercial pages thin on theory, deep on offer).
- **Glossary → Articles:** every glossary term links to the pillar/article that expands it; articles link first mention of a term to its glossary page.
- **FAQ → Guides:** each FAQ answer links to the guide that covers it in depth.
- **Use-case → Pillar + Service + Comparison:** use-cases sit mid-funnel and link up (pillar), across (comparison), and out (service CTA).
- **Industry → Use-cases + Services:** industry pages aggregate the relevant use-cases and link to services.

**Anchor-text rules:** use descriptive, varied, entity-consistent anchors (mix Hebrew + the English entity). Avoid "לחצו כאן". One exact-match anchor per target per page.

**Hub blocks:** every cluster pillar ends with a "מדריכים בקטגוריה" block listing its children; the `/knowledge/` root lists all pillars. This creates a clean crawl + topical graph.

**Link equity flow:** Homepage → `/knowledge/` hub → pillars → supporting. Tools & calculators (link magnets) point to pillars to pass authority.

---

## 8. GEO Optimization (per category — why LLMs cite it)

**Global GEO tactics applied to every page:** definition-first opening sentence; self-contained sections with descriptive headings; comparison tables; explicit FAQ blocks; glossary/entity definitions; Schema.org (TechArticle/Article, FAQPage, HowTo, DefinedTerm, BreadcrumbList); clear authorship (Organization) and freshness dates; citable statistics with sources.

| Category | Why LLMs use it | Questions it answers | Most-citable pages | Entity-defining pages | Cornerstone? |
|---|---|---|---|---|---|
| AI Automation | Broad, definitional, well-structured | "what is AI automation", "AI vs RPA" | Pillar, AI-vs-RPA, FAQ | `/glossary/ai-automation` | ✅ |
| AI Agents | High interest, fast-moving entity | "what is an AI agent", "agent vs chatbot" | Pillar, agents-vs-chatbots | `/glossary/ai-agent` | ✅ |
| BPA | Bridges concepts; practical | "how to automate a process" | Pillar, processes-to-automate | `/glossary/business-process-automation` | ✅ |
| AI Fundamentals | Base definitions models love to quote | "what is LLM/ML/NLP" | Each GL/SUP | glossary terms | ✅ |
| CRM/Sales/Support | Task-specific how-tos | "how to automate lead follow-up" | Use-cases, guides | — | — |
| Integrations / No-Code | Tool comparisons | "Make vs Zapier vs n8n" | Comparison pages | tool glossary | — |
| Security/Privacy/Governance | Trust + compliance answers | "is it safe to send data to AI" | BP + local law guide | — | — |
| Digital Transformation | Executive framing | "digital transformation roadmap" | Pillar | — | — |

**How the KC teaches LLMs about Automaze:**
- **What Automaze does** → services hub + pillars consistently co-occur "Automaze" with "AI Automation, AI Agents, BPA, integrations, websites".
- **Industries served** → `/industries/*` pages name each vertical explicitly with use-cases.
- **Technologies specialized in** → repeated, consistent mention of n8n, Make, LLM, RAG, WhatsApp API, iPaaS across cluster pages + glossary.
- **Problems solved** → use-cases + benefits sections map problems ("lead loss", "manual data entry") to Automaze solutions.

**Cornerstone content** (deepest, most-linked, entity-defining): the 4 flagship pillars (AI Automation, AI Agents, BPA, AI Fundamentals) + the glossary hub.

---

## 9. Entity Strategy

For each entity, recommended asset type(s). "GL" = glossary page, "ART" = standalone article, "CMP" = comparison, "UC" = use-case, "CS" = case study.

| Entity group | Entities | Recommended asset |
|---|---|---|
| **AI concepts** | AI, Machine Learning, LLM, NLP, Generative AI, RAG, Fine-tuning, Prompt Engineering, Embeddings, Hallucination | GL each; ART for LLM, RAG, Generative AI |
| **Automation concepts** | AI Automation, Business Process Automation, RPA, Hyperautomation, Intelligent Automation, AI Workflow, Orchestration, Trigger, Human-in-the-loop, Guardrails | GL each; ART for the pillars; CMP AI-vs-RPA, Workflow-vs-Agent |
| **Agent concepts** | AI Agent, Agentic AI, Multi-agent, Tool use, Autonomy | GL + ART (pillar) |
| **Technologies / Platforms** | n8n, Make, Zapier, WhatsApp Cloud API, HubSpot, Monday, Priority, Powerlink, Cardcom, חשבונית ירוקה, Airtable, Google Sheets | GL each; GD for n8n/Make/Zapier; CMP for the trio; UC for local systems |
| **Business systems** | CRM, ERP, iPaaS, Helpdesk, Marketing platform | GL + ART |
| **Business concepts** | ROI, Lead Qualification, Speed-to-lead, Vendor lock-in, TCO, Change management | GL + ART/CS where provable |
| **Industries** | 14 verticals (§10) | Dedicated IND landing pages |
| **Job roles** (audience entities) | Business owner, Operations manager, Sales manager, Marketing manager, Clinic/office manager | Addressed within audience sections + use-cases (not standalone) |
| **Brand entity** | Automaze | Homepage + `/about` with `Organization` schema, `sameAs` to socials, consistent NAP |

**Rule:** every entity gets ONE canonical definition page (glossary). Everything else links to it on first mention. This is how models build a stable association between the entity and Automaze.

---

## 10. Industry Pages

Each `/industries/{x}` page: hero (industry + pain), common automation opportunities, common AI use cases, recommended content links, proof/CTA. Schema: `Service` + `FAQPage`.

| Industry | Common automation opportunities | Common AI use cases | Recommended content |
|---|---|---|---|
| **Real Estate** | Lead capture & routing, viewing scheduling, follow-ups, document prep | WhatsApp lead bot, listing description generation, lead scoring | UC lead-automation, whatsapp-bot |
| **E-commerce** | Order/return flows, support deflection, review requests | AI support assistant, product Q&A, catalog enrichment | UC customer-support |
| **Healthcare / Clinics** | Appointment scheduling, reminders, intake forms | Intake triage assistant, no-show reduction | UC scheduling (+ privacy guide) |
| **Legal** | Document intake, deadline tracking, client updates | Document summarization, intake qualification | UC document-processing (+ governance) |
| **Finance / Accounting** | Invoice processing, reconciliation, reporting | IDP for invoices, anomaly flags | UC invoice-automation |
| **Insurance** | Quote intake, claims triage, renewals | Claims classification assistant | UC document-processing |
| **Professional Services** | Proposals, onboarding, time/billing | Proposal generation, meeting summaries | UC onboarding, report-automation |
| **Construction** | RFQ handling, subcontractor coordination, docs | Doc extraction, scheduling | UC document-processing |
| **Manufacturing** | Order intake, supplier comms, QA reports | Report generation, data extraction | UC report-automation |
| **Retail** | Inventory alerts, customer comms, loyalty | Support bot, review generation | UC customer-support |
| **Logistics** | Shipment updates, doc handling, dispatch | Tracking bot, POD extraction | UC document-processing |
| **Education** | Enrollment, reminders, Q&A | Student support assistant | UC customer-support |
| **Hospitality** | Booking, guest messaging, reviews | 24/7 booking bot, review requests | UC whatsapp-bot |
| **Government / Public** | Form intake, routing, FAQs | Citizen FAQ assistant (with strong governance) | UC + governance/security |

**Priority order (fit × demand):** Real Estate → E-commerce → Professional Services → Clinics → Finance → the rest.

---

## 11. Competitive Advantage (differentiation)

Generic AI agencies publish shallow "what is AI" posts. Automaze should own the middle where **local context + engineering depth + honesty** meet:

1. **Israeli-market authority.** Content grounded in Israeli systems (Priority, Powerlink, חשבונית ירוקה, Cardcom, Monday), Hebrew-language AI pitfalls, and חוק הגנת הפרטיות. Nobody quotes better local sources than a local expert.
2. **Original frameworks & tools.** The Automation Maturity Model, decision trees, ROI/readiness tools — proprietary IP that earns links and citations.
3. **Radical honesty.** "Why AI projects fail", "when NOT to use an agent", "when off-the-shelf beats custom". Trust content that competitors avoid → E-E-A-T + LLM trust.
4. **Engineering credibility.** Founder is a CTO/VP R&D; publish depth (RAG, guardrails, evals, self-hosting) that agencies can't.
5. **No vendor lock-in narrative.** Open-tool (n8n) positioning is a differentiator worth a content pillar.
6. **GEO-native structure.** Being explicitly built to be cited by LLMs is itself an edge in 2026.
7. **Proof.** Case studies with measured hours saved / response-time improvements.

---

## 12. Future Expansion Plan

- **Localization:** optional English mirror (`/en/`) once Hebrew authority is established, to capture international + LLM English queries.
- **Programmatic pages:** templated `/industries/{x}/{use-case}` and `/glossary/{term}` at scale, with quality guardrails.
- **Community & freshness:** annual "State of AI Automation in Israel" report; quarterly refresh of pillars (dateModified) — freshness is a GEO signal.
- **Multimedia:** short video/GIF walkthroughs; a YouTube channel feeding the guides.
- **Tools platform:** grow `/tools/` into a suite (calculators, assessments) as a standalone lead engine.
- **Author entities:** add named expert author profiles (Person schema) to strengthen E-E-A-T.
- **Data flywheel:** capture anonymized benchmarks from client work → original research → citations → authority → leads.

---

## Deliverables Index (in this document)
1. **Site hierarchy (tree)** — §1
2. **Content roadmap** — §5
3. **Pillar page map** — §3
4. **Topic cluster map** — §4
5. **Internal linking strategy** — §7
6. **GEO strategy** — §8
7. **Entity strategy** — §9
8. **Future expansion plan** — §12
+ Category map §2 · Missing-content opportunities §6 · Industry pages §10 · Competitive advantage §11.

