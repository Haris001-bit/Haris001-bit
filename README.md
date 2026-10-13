# Muhammad Haris

**AI engineer.** I build production AI platforms end to end: the product, the AI agents and retrieval inside it, and the security and data architecture underneath.

Founding AI engineer at a fintech, AI lead on a multi-tenant compliance platform, and builder of AI agents that have handled 6,700+ real customer conversations. Usually the engineer who takes a system from scoping through to production and handover.

---

## What I've shipped

### Platforms

**AI agent layer and security for a fintech.** For an early-stage fintech handling users' financial data, read-only by design: a research agent with guardrails and a streaming safety filter, an MCP server with hashed, revocable access tokens, and the security programme around users' financial data: two-step sign-in enforced in the database, versioned consent records, rate limits, row-level security, monitoring and a CI security gate.

**Multi-tenant AI compliance platform.** AI lead on a GRC platform with 16 specialised AI personas: hybrid retrieval with cross-encoder reranking, per-tenant access control enforced at retrieval, graph memory, browser automation and RAG evals, plus a tiered latency pipeline that cut 3 to 8 seconds from every follow-up message.

**Bank-feed financial module inside a live SaaS.** Business bank and card feeds combined with CRM revenue, built inside an existing field-service app without breaking it: encrypted tokens, signed webhooks, owner-only row-level security, per-company isolation, a deterministic calculation engine, self-service setup, and no bank data in any AI tool.

**Compliance operations platform for a specialised school.** A full-stack Next.js app with role-based access for 7 staff roles, compliance monitoring, CRM sync and scheduled jobs, plus a Power Automate layer for staff-facing workflows.

**Native iOS and Android launch.** A marketplace app taken from a web codebase to both app stores from a Windows machine with no Mac, through a full store-compliance pass. Approved on the first App Store submission.

### Production AI systems

**AI customer support agent for a UK broadband provider.** 6,700+ conversations, 2,400+ tickets automated, 21,000+ agent minutes saved. It checks the CRM and live outages mid-chat and routes escalations across 7 departments.

**WhatsApp retention engine for the same provider.** Consent-gated personalised offers with SMS fallback, AI reply handling and a ticketed handover to the retention team.

**Email and web-form intake for a translation company.** A 224-node email workflow and a 38-node webhook workflow on self-hosted n8n, with schema-locked AI steps, a compliance pass, and a non-AI gate that withholds a bad draft and escalates to a human.

**Change detection at scale.** A pipeline monitoring tens of thousands of entities in an external directory with no change feed: two-stage confirmation, append-only snapshots and cross-source corroboration, built around the fact that false positives cost far more than delay.

**White-label automation.** One AI vision estimation product deployed across 7 customer sites, each with its own pricing, identity and destinations, maintained by one engineer.

---

## Repositories

Engineering write-ups from the systems above: the problem, the tradeoffs and how I resolved them, the failure modes, and what I'd do differently.

| Repo | What it is |
|---|---|
| [fintech-ai-agent-security](https://github.com/Haris001-bit/fintech-ai-agent-security) | Securing AI agents on private financial data: guardrails, an MCP server with revocable tokens, database-enforced controls proven in CI |
| [multi-tenant-rag-architecture](https://github.com/Haris001-bit/multi-tenant-rag-architecture) | Design notes from a production RAG platform: retrieval, reranking, tenant isolation, latency tiering |
| [bank-feed-financial-module](https://github.com/Haris001-bit/bank-feed-financial-module) | Bank feeds plus CRM revenue inside a live SaaS: token encryption, tenancy, a property-tested sorter, a deterministic engine |
| [compliance-operations-platform](https://github.com/Haris001-bit/compliance-operations-platform) | Access control by structure for sensitive records, plus the automation layer around it |
| [web-app-to-app-stores](https://github.com/Haris001-bit/web-app-to-app-stores) | Shipping a web app to the App Store and Google Play without a Mac, and getting approved by Apple on the first submission |
| [ai-customer-support-agent](https://github.com/Haris001-bit/ai-customer-support-agent) | A support agent that calls live systems mid-conversation, and decides what a human should handle |
| [whatsapp-retention-engine](https://github.com/Haris001-bit/whatsapp-retention-engine) | Event-driven retention messaging: consent gates, duplicate guards, held events, AI reply handling |
| [multi-inbox-email-triage](https://github.com/Haris001-bit/multi-inbox-email-triage) | Email and web-form automation: idempotency, thread identity, three layers of output safety, never auto-send |
| [change-detection-pipeline-patterns](https://github.com/Haris001-bit/change-detection-pipeline-patterns) | Patterns for detecting state changes in systems you don't control |
| [white-label-automation-architecture](https://github.com/Haris001-bit/white-label-automation-architecture) | One product, seven customer deployments: clone-per-tenant tradeoffs, config as data, vision estimation |
| [vision-document-extraction](https://github.com/Haris001-bit/vision-document-extraction) | Structured data out of layout-heavy documents: scatter-gather extraction, data contracts, entity matching |

These are engineering write-ups rather than client deliverables. Client work is published only with the client's permission, and never includes source, credentials, customer data or anything that identifies the client. That's a standard I'd apply to your project too.

---

## Stack

**AI** Claude and OpenAI APIs · agents · MCP · RAG (hybrid retrieval, reranking, pgvector) · evals
**Product** Next.js · React · TypeScript · Python · FastAPI · .NET · Supabase and Postgres · Vercel · Docker
**Mobile** Capacitor · iOS and Android store release
**Integrations and automation** Plaid · Microsoft Graph · Google APIs · CRMs · n8n · Make · Zapier · Power Automate
**Voice and messaging** Voiceflow · Retell · Vapi · ElevenLabs · WhatsApp Cloud API · Twilio
**Engineering** Claude Code · GitHub Actions · Playwright · Sentry

---

## How I work

**Architecture comes first.** Tenant isolation and row-level security, strict output schemas on every AI step, evals, human approval where a mistake costs money, and monitoring in production.

**AI-native, with the discipline kept.** I build with Claude Code, in small reviewed pull requests with automated tests and CI gates on every change, so speed never costs reliability.

**Failure handling before features.** Retries, idempotency, rate-limit awareness and blast-radius caps get built in from the start. Automation that only works on the happy path is a demo.

**Documentation is part of the deliverable.** Every system I hand over comes with architecture docs explaining what it does, what's safe to change, and how to fix it at 2am.

**I'll tell you what won't work.** Including when the thing you asked for isn't the thing you need.

---

## Get in touch

Available for AI platform, agent and automation engineering, contract or full-time, remote.
