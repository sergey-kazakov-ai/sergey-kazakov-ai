# Hi, I'm Sergey 👋

**Solutions / AI Automation Engineer** — I build production AI agents, integrations & full-stack tools for real businesses.

📍 Israeli citizen (full work authorization) · Tel Aviv area · 📫 kazaksg@gmail.com · [Portfolio](https://sergey-kazakov-ai.github.io) · [LinkedIn](https://www.linkedin.com/in/sergey-kazakov-ai)

---

## What I've shipped

Everything below was built for a **real business** — most of it runs in production today; none of it is a tutorial project. The codebases are private (live business code), so each link goes to a write-up with architecture and screenshots.

### 🤖 [AI Sales Agent — conversational commerce in production](https://sergey-kazakov-ai.github.io/#projects)
Customer-facing agent selling across a **15,000-SKU catalog**: multi-tool LangChain orchestration, hybrid RAG (pgvector + SQL), supplier-search fallback with price/delivery calculation, cost-aware model routing, Redis debounce, human-in-the-loop handoff.
`n8n` `LangChain` `OpenAI` `Supabase` `PostgreSQL` `Redis`

### 🏗 [StroyKontrol — construction ERP from scratch](https://sergey-kazakov-ai.github.io/#projects)
**~43k LOC** full-stack ERP replacing a ~$800/mo commercial SaaS: 47-entity data model with RLS multitenancy, document-AI (Gemini Vision → structured JSON with token-based billing), custom Excel estimate tree-parser, fuzzy material matching. Unit + e2e tests.
`Next.js` `React` `TypeScript` `Supabase` `Gemini` `Playwright`

### 🔗 [Bitrix24 ↔ 1C ↔ Website — deep CRM↔ERP integration](https://sergey-kazakov-ai.github.io/#projects)
Two-way integration (multi-warehouse, multi-org): custom deal widget turning multi-step ERP operations into a few clicks, full payment domain (acquiring, bank-statement auto-classifier, signed webhooks), custom HTTP service inside the ERP, and an **AI pipeline that generates ERP extension modules** with automated deploy/rollback.
`PHP` `1C/BSL` `Python` `REST` `webhooks` `MCP`

### ⚙️ Also built
- **4 production MCP servers** (official SDK, Railway) — incl. a Google Ads server that **passed Google's OAuth app verification** and replaced an outsourced agency
- **Multi-agent business assistant** (built, pre-production) — cost-aware Claude routing (Haiku→Sonnet→Opus), MCP bridge to company data, ABC/XYZ supply analytics
- **Entity-resolution engine** — weighted product matching without unique IDs, anti-bot scraping
- **Telegram ops bots** — logistics, receivables, bank-RPA

---

## How I work

I'm an **AI-leveraged engineer**: I design the architecture, orchestrate modern LLMs end-to-end, integrate, deploy, and own the result in production. 15+ years of business background (e-commerce, official Asus service operation, deep 1C:Enterprise) — I speak both engineering and business.

**Open to:** Solutions Engineer · AI/Automation Engineer · Integration Engineer · Customer Success Engineer — Tel Aviv area or remote, available immediately.
