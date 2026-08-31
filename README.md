# 👋 Hi, I'm Robert

🎓 Computer Science student at Alexandru Ioan Cuza University, Iași, Romania
💻 Full-stack developer — I build and ship production web platforms, not just coursework
🌍 Open to internships or entry-level roles (remote or relocation)

I work mainly with **TypeScript, Next.js and PostgreSQL**, building e-commerce platforms and supplier API integrations. I'm also the person who handles everything around the code — deployment, DNS, SEO and branding — because in small teams someone has to.

My recent work lives in private repositories (client and business projects), so the summaries below describe what I built and the stack behind it. Happy to walk through any of it in detail.

---

## 🚀 What I'm building

### 🛍️ MOFT — B2B/B2C e-commerce platform for personalized products
*Full rebuild of a commercial platform · sole developer · private repo*

A hybrid B2B/B2C store for promotional items and custom textiles, replacing a legacy template-based site.

- **Multi-supplier catalog sync** — async ETL pipelines that normalize products, variants and live stock from three suppliers (Malfini via OpenAPI, Roly and Stamina via the Gorfactory API) into a unified PostgreSQL schema: **~2,400 products, 38,000 SKUs and 10,000 colour variants**, with stock levels kept current
- **B2B flow** — stock/variant matrix, tiered pricing, and a request form that generates PDF quotes
- **B2C flow** — Stripe checkout, customer accounts and order history, multiple delivery options
- **Admin panel** — products, orders, quote requests, customers, categories, seasonal collections, site content, commercial markup tiers and sync management, with role-based access for the client's team
- Deployed on Vercel with a separate staging environment, DNS managed through Cloudflare

**In progress:** the Web-to-Print personalization editor — a canvas-based editor with real-time DPI quality checking and server-side export of 300 DPI print-ready files. It's the hardest part of the platform and I'd rather build it properly than ship it half-working.

`Next.js` `TypeScript` `Supabase / PostgreSQL` `Stripe` `Tailwind CSS` `Anime.js` `Vercel` `Cloudflare`

---

### ⚡ SuperLED — brand site & search visibility
*Web and technical lead for an LED lighting and electrical materials business · [superled.ro](https://superled.ro)*

I own everything digital for this business: the site, the brand and the search presence.

- Designed and built the site, plus the full visual identity — logo system, palette, favicon, invoice header and thermal-printer assets
- **Technical SEO** — Schema.org structured data (`LocalBusiness`, `FAQPage`), sitemap, Google Search Console and Business Profile setup, plus a series of Romanian-language articles targeting real product search queries
- Planned and ran Google Ads acquisition campaigns, and handled domain, DNS and deployment end to end

`HTML/CSS` `JavaScript` `GSAP` `GitHub Pages` `Cloudflare` `Schema.org`

---

### 🖨️ RobiPrinting3D — 3D printing operation
*Side venture I founded and run*

Small-scale production printing on Bambu Lab hardware — B2C items sold through Instagram and TikTok, plus B2B bulk orders from local businesses.

- Build the audience and take orders directly through social channels
- Handle the unglamorous half too: costing, pricing, sourcing and customer communication

`3D modeling / STL` `Bambu Lab`

---

## 🤖 How I work with AI tooling

I use LLMs as part of my actual engineering process, with structure around them rather than ad-hoc prompting:

- **Multi-agent workflow in Claude Code** — a planner model drafts the approach, an implementer writes the code, a cheaper model runs checks, and a reviewer model does the code review pass
- **Context engineering at repo level** — `CLAUDE.md` and `AGENTS.md` as persistent project instructions so the model works from the project's real conventions
- **Custom skills** — I write project-specific skill files (animation and motion rules, UI/UX standards, polish passes) alongside third-party ones, so quality standards are enforced automatically instead of re-explained every session

The point isn't writing code faster. It's keeping quality consistent across a codebase I'm maintaining alone.

---

## 🛠️ Tech Stack

**Languages** — TypeScript · JavaScript · Java · C / C++ · PHP · SQL
**Frontend** — Next.js · React · Tailwind CSS · Vue.js · HTML/CSS · GSAP · Anime.js
**Backend & data** — Node.js · PostgreSQL · Supabase · MySQL · SQLite · REST / OpenAPI integrations
**Infra & tools** — Git · Vercel · Cloudflare · GitHub Pages · Linux & Bash · Playwright
**Adjacent** — Technical SEO · Google Search Console & Ads · Brand and UI design

---

## 🎓 Education & certifications

**BSc Computer Science** — Alexandru Ioan Cuza University, Iași · 2022 – present

| Certification | Issuer | Date |
|---|---|---|
| Java Development | Google Digital Garage | Feb 2023 |
| Responsive Web Design | freeCodeCamp | Nov 2022 |

### Course & university projects

| Project | Stack | What I did |
|---|---|---|
| **Smart Parking Lot** | Vue.js, TypeScript, Tailwind | Built the front-end for a real-time parking availability app — UI, API integration, live updates |
| **Quoridor** | C / C++ | Digital version of the board game: game logic, player movement, interface |
| **Web Technologies** | PHP, JS, SQL | Dynamic pages, authentication, database layer |
| **Java Catalog** | Java | Desktop app for managing students, grades and averages — built during the Google Digital Garage Java course |
| **Employee CRUD** | Java | CRUD application built around OOP principles — built during the Google Digital Garage Java course |
| **OOP Exercises** | C++ | Classes, inheritance, file I/O, basic algorithms |

---

## 🎯 Currently focused on

- Backend architecture and third-party API integrations at scale
- Performance and animation quality on the front-end
- Shipping things people actually use

---

## 🗣️ Languages

Romanian (native) · English (professional working proficiency)

---

## 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/robertolariu90)

Based in Iași, Romania. Open to remote work or relocation.
