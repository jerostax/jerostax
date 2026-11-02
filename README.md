# Hi, I'm Jérémy Geneste 👋

**Full-Stack JavaScript / TypeScript Developer** · React · Next.js · Node.js · Generative AI<br>
Paris, France · Freelance, open to full-time roles and contracts

🌐 [jeremy-geneste.com](https://jeremy-geneste.com/) · 💼 [LinkedIn](https://www.linkedin.com/in/jeremy-geneste/) · 📂 Public code: [jerostax/jeremy-geneste](https://github.com/jerostax/jeremy-geneste), the source of my site (Next.js 16, TypeScript, tests and required CI)

Full-stack JavaScript developer since 2019: **5 years at an IT services company** (EdifiXio / Atos / Eviden) building business web applications for higher education, insurance, and services clients, now **freelancing**. I work from the UI down to the database: REST APIs, PostgreSQL, third-party integrations, technical SEO, and testing.

## 🏢 Delange Immobilier — freelance, since Oct. 2026

Sole developer of a Paris real estate agency's website, working directly with its management. Took over an existing Next.js 15 / React 19 application.

- **Takeover and security:** code audit (~25 prioritized issues, 3 critical), secured admin and API access, security headers (CSP) checked by E2E tests.
- **Hosting migration** (GitHub, Vercel, PostgreSQL/Neon, DNS) to agency-owned accounts with no downtime; identified the real production database beforehand (283 customer requests preserved).
- **Business integrations:** website inquiries flowing into the Apimo CRM again (blocked for 10 months); legally required fee and condominium disclosures, with rules as tested pure functions.
- **SEO and performance:** server-rendered listings, metadata, and structured data; homepage reduced from 21 to 3.7 MB and mobile LCP from 88.7 to 4.0 s (PageSpeed Insights).
- **Quality:** 21 isolated Playwright E2E tests (mock CRM, test database) and unit tests run before every PR.

## 🤖 AI website generation SaaS — personal project, since Jan. 2026

With a business analyst: scoping since January 2026, development since September 2026, as the sole developer. MVP live, no customers yet.

- **Generative AI:** Gemini content generation with structured output (JSON schema) validated by Zod, run as a background job with state tracking; safeguards against AI fabrication; AI-suggested colors with checked contrast (WCAG).
- Ordering flow through confirmation, 6 languages, all client sites served by a single deployment and routed by domain; 119 unit tests.

Next.js 16 · Prisma · PostgreSQL · Gemini · Vercel

## 🛠️ AI-assisted development, with guardrails

I use Claude Code daily, with a version-controlled setup I maintain:

- rules and permissions: no access to secrets (`.env`), a Python hook that blocks any push to `main` (30+ cases tested), one pull request per topic, human approval;
- read-only security and SEO audit agents and a `/pr-ready` skill, used on the Delange engagement;
- Notion tracking driven from Claude Code (MCP): tickets, achievements log, client follow-up page.

AI speeds things up; architecture and code quality remain my responsibility.

## Stack

| Area | Technologies |
|---|---|
| **Front end** | React, Next.js, TypeScript, JavaScript, Tailwind CSS, Angular, Ionic |
| **Back end & data** | Node.js, Express, REST APIs, PostgreSQL, MongoDB, Prisma, Zod |
| **Testing & quality** | Playwright, Vitest, GitHub Actions, pull request reviews |
| **Cloud & integrations** | Vercel, Neon, Heroku, AWS, Salesforce, Jira, Apimo |
| **AI** | Claude Code (agents, skills, hooks, MCP), Gemini API |

> 🔒 Client and SaaS code is private. Happy to walk through the architecture and my contributions in an interview.
