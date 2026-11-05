# 👋 Mohit Kadyan

**Full-Stack AI Developer** — I build MVPs, ship full-stack products, 
and wire the automation that runs the business behind them.

Most developers do one or the other. I do both.

📍 Rohtak, India &nbsp;|&nbsp; 
🌐 [Portfolio](https://mohit-resume20.netlify.app/) &nbsp;|&nbsp;
💼 [LinkedIn](https://linkedin.com/in/mohit-kdyn) &nbsp;|&nbsp;
🐙 [GitHub](https://github.com/Kadyan25)

---

## 🚀 What I Build

Production-grade full-stack SaaS, AI-integrated products, 
and automation pipelines — tested, deployed, and ready for 
real users. Not prototypes. Not demos.

- **Full-stack SaaS** — multi-tenant architecture, OAuth, 
  role-based access, payments (Stripe), CRM sync, Redis caching
- **AI integration** — Claude, Gemini, OpenAI for agentic 
  tool-calling, RAG pipelines, AI summaries, voice agents (Vapi)
- **Automation** — production n8n workflows covering lead gen, 
  CRM pipelines, missed-call recovery, AI marketing campaigns
- **Testing** — unit, integration, and Playwright E2E across 
  every project. I don't deploy without coverage.

---

## 🏗️ Shipped & Live

### Exchange Four SEO Engine — Autonomous Multi-Site SEO Agent
Headless agent that researches topics, writes and publishes articles, improves pages close
to ranking, audits sites weekly, and measures what happened — running on a schedule across
multiple real sites from one process (Exchange Four's own site on Supabase, Compass
Registered Agent on WordPress). Approval policy lives entirely in code, not in the model:
every action is tier-classified, and anything irreversible — deleting a page, spending
money, outreach — waits for a signed human approval link before it runs.  
**Stack:** Python, Claude Agent SDK, Supabase, WordPress REST API, Railway  
**Tests:** 3,500+ Pytest unit/integration tests (hermetic, no network) plus a
mutation-testing harness that deliberately breaks each safety guard to confirm a test
catches it

---

### [Onelytics](https://onelytics-production.up.railway.app) — Marketing Analytics SaaS
Multi-tenant SaaS unifying GA4, Google Ads, Meta, TikTok, 
LinkedIn, Search Console via OAuth. Claude AI summaries, 
Redis caching, AES-256 token encryption, role-based workspaces.  
**Stack:** Next.js 14, PostgreSQL, Prisma, Redis, Claude API, Railway  
**Tests:** Unit, integration, Playwright E2E (tenant isolation, 
token refresh, role-based UI, invite flow)  
[GitHub](https://github.com/Mohit02026/onelytics) · 
[Live](https://onelytics-production.up.railway.app)

---

### [Exchange Four](https://exhange4hr-production.up.railway.app/) — HR & Personnel Management Platform
Full HR lifecycle platform — application, onboarding, 
performance reviews, disciplinary actions, offboarding. 
Multi-stage approval chains with secure single-use tokens, 
3-tier RBAC, automated document generation (NDAs, contracts), 
CRM sync via signed webhooks, automated weekly reports.  
**Stack:** Next.js 14, PostgreSQL, Prisma, NextAuth, 
Resend, GoHighLevel, Railway  
**Tests:** 13+ Playwright E2E suites + full Vitest 
integration coverage across every workflow

---

### [Compass Registered Agent](https://github.com/Mohit02026/compassRA) — LLC Formation Platform
Client-facing platform for LLC formation with Stripe checkout, 
document portal, compliance calendar, and stage-based ops 
workbench (INTAKE → DATA_QC → READY_TO_FILE → FILED → COMPLETED). 
Bidirectional GoHighLevel CRM sync via signed webhooks, 
Cloudflare R2 document storage, PDF generation.  
**Stack:** Next.js 14, TypeScript, Prisma, PostgreSQL, 
Stripe, GoHighLevel, Resend, Cloudflare R2, Railway

---

### [AI Counsellor](https://ai-counsellor-umber.vercel.app) — Agentic University Admissions Platform
Agentic AI platform where Claude/Gemini perform real database 
operations (shortlist universities, lock choices, create tasks) 
via validated JSON tool calling. Multi-provider AI with 
automatic fallback and hallucination prevention — AI cannot 
invent data not in the database.  
**Stack:** Spring Boot, Next.js, PostgreSQL, JWT, 
Docker, Gemini API, OpenRouter, Perplexity  
[GitHub](https://github.com/Kadyan25/ai_counsellor) · 
[Live](https://ai-counsellor-umber.vercel.app)

---

### [Inboxd](https://inboxd-production-077c.up.railway.app) — AI-First Email Client
Unified inbox across Gmail, IMAP (Yahoo/AOL), and Outlook. 
Claude Sonnet powers AI summaries, 3-strategy reply drafts, 
and priority triage (URGENT/NORMAL/LOW/NOISE) on every sync. 
Full PWA with offline shell.  
**Stack:** Next.js 14, PostgreSQL, Prisma, NextAuth, 
Claude API, Gmail REST API, IMAP, Railway  
**Tests:** 80 Vitest unit tests + Playwright E2E  
[GitHub](https://github.com/Kadyan25/Inboxd) · 
[Live](https://inboxd-production-077c.up.railway.app)

---

### [Research Intelligence System](https://agentic-wiki.onrender.com) — Multi-Agent AI Pipeline
7-agent pipeline turning text, PDFs, images, URLs, or CSVs 
into a cross-linked knowledge base. Deterministic agents 
(intake, extraction, linking) handle zero-cost tasks; 
LLM agents (Claude Sonnet/Haiku) reserved for reasoning, 
writing, and quality validation. Semantic RAG via Google 
embeddings + cosine similarity.  
**Stack:** Python, FastAPI, Claude API, 
Google Embeddings, Qdrant, Render  
[GitHub](https://github.com/Kadyan25/agentic-wiki) · 
[Live](https://agentic-wiki.onrender.com)

---

### [n8n Automation Portfolio](https://github.com/Kadyan25/n8n-workflows-portfolio) — 14 Production Workflows
AI marketing campaign pipeline (5 connected flows), B2B lead 
generation (dual Apify scrapers + AI-configured targeting + 
email verification), missed-call recovery, GoHighLevel CRM 
automation, LinkedIn outreach system, RAG agent pipelines.  
**Stack:** n8n, Claude/Gemini/OpenAI agents, GoHighLevel, 
Apify, Google Sheets API, Vapi, webhooks

---

### [SEO Audit Tool](https://github.com/Kadyan25/seo-audit-tool) — Technical SEO Crawler
Production-grade crawler auditing 200+ pages per run — 
broken links, meta tags, Core Web Vitals via PageSpeed API, 
JS-rendered SPA support. Background job queue, concurrent 
multi-site audits, PDF/CSV report export. Fully Dockerized.  
**Stack:** Python, FastAPI, Playwright, 
async httpx, Docker, Google PageSpeed API

---

## 💻 Tech Stack

### Languages
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

### Frontend
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend
![Spring Boot](https://img.shields.io/badge/springboot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

### Databases & Caching
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)

### AI & Automation
![Claude](https://img.shields.io/badge/Claude-181818?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)

### Auth & Security
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![OAuth](https://img.shields.io/badge/OAuth-2.0-blue?style=for-the-badge)

### DevOps & Deployment
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-131415?style=for-the-badge&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

### Tools
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 🤝 Open To

Full-stack development, AI engineering, and automation roles 
where I can own the build end-to-end — not be managed through it.

**LinkedIn:** [linkedin.com/in/mohit-kdyn](https://linkedin.com/in/mohit-kdyn)  
**Portfolio:** [mohit-resume20.netlify.app](https://mohit-resume20.netlify.app/)
