# 👋 Hi, I'm Arsenii Ostroumov

**Automation / Integration Engineer** focused on workflow automation, API integrations, and applied LLM systems.

I build production-oriented solutions that connect business processes with reliable execution: APIs, webhooks, bots, data pipelines, and AI-assisted workflows. My focus is not just prototyping, but making automation stable in real use with validation, retries/backoff, deduplication, and observability.

---

## What I do

- **Workflow automation** — n8n, API orchestration, webhooks, background processing, event-driven flows
- **AI systems** — RAG assistants, structured LLM outputs, citation-first answers, validation and fallback flows
- **Integrations** — CRM, messaging, external APIs, Google services, accounting and internal business systems
- **Backend & data** — Python, FastAPI, PostgreSQL, SQL, pgvector, service logic, error handling
- **Production reliability** — idempotency, retries, timeout handling, audit trails, incident-friendly logging

---

## Featured projects

### [AI Support RAG Assistant](https://github.com/ArsenYoung/ai-support-rag-assistant)
Knowledge base assistant with retrieval, confidence thresholding, and citation-based answers.
- RAG pipeline: ingest → chunking → embeddings → vector search → grounded response
- Hallucination control with **ALLOW / CLARIFY / NO_ANSWER**
- Webhook contracts for ingest and answer flows
- Telemetry for `top_score`, latency, and sources per turn

### [AI Market Screener](https://github.com/ArsenYoung/ai-market-screener)
Telegram bot for crypto/X threat intel with immediate risk alerts and daily digest.
- Processes incoming text and turns it into structured risk signals
- Supports alerting and digest workflows
- Designed as a reusable AI triage pattern for operational workflows

### [ProductCard AI Bot](https://github.com/ArsenYoung/productcard-ai-bot)
Telegram bot and CLI for generating structured product/content cards with a local LLM.
- Structured JSON generation with retry on invalid output
- Local LLM setup via Ollama
- Reusable pattern for product, content, and internal drafting workflows

### [Lead Capture: Webhook → Google Sheets → Telegram](https://github.com/ArsenYoung/lead-capture-gas-tg)
Lightweight lead intake automation for forms and small growth workflows.
- Captures webhook payloads into Google Sheets
- Sends formatted Telegram alerts with lead context
- Adds predictable error handling and logging for incoming payloads

---

## Tech stack

**Python · FastAPI · JavaScript / TypeScript · n8n · PostgreSQL · SQL · pgvector · Docker · REST APIs · Webhooks · OpenAI API · Telegram Bot API · Google Apps Script · Supabase**

---

## What I care about

I’m interested in systems that make business operations faster, more reliable, and easier to scale.  
The best work for me sits at the intersection of **automation, integrations, backend engineering, and applied AI** — especially where the result is measurable in reduced manual work, clearer processes, and better operational reliability.

---

## Contact

- Telegram: **@arseniy_ostroumov**
- LinkedIn: **[arseniy-ostroumov](https://www.linkedin.com/in/arseniy-ostroumov/)**
- Email: **ostroumov.arsenii@gmail.com**
