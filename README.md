# Muhammad Haris

**AI Automation Engineer.** I build production automation systems that run unattended and don't wake anyone up at 3am.

Roughly two years in, self-taught, Make.com Advanced Certified. Most of my work is voice AI, multi-channel workflow automation, and retrieval systems, usually as the only engineer on the project, from scoping through to handover.

---

## What I've shipped

**Voice AI at real volume.** A conversational voice agent and chatbot pair for a UK fibre ISP: **6,700+ conversations**, **2,400+ support tickets** raised automatically, **21,000+ minutes** of handled call time. Address validation, outage checks, CRM lookups and prospect creation, with clean escalation to humans where automation shouldn't decide.

**Large-scale email automation.** A **182-node** n8n workflow triaging live mail across **9 Outlook inboxes** for a translation company: classification, threading, attachment handling, document-request detection, and templated response generation, in production and iterating against real traffic.

**Multi-tenant RAG platform.** Architected retrieval for a compliance/GRC product: hybrid dense + lexical retrieval, cross-encoder reranking, role-scoped knowledge isolation, and a tiered latency pipeline that cut 3 to 8 seconds from every follow-up message.

**Change detection at scale.** A pipeline monitoring tens of thousands of entities in an external directory with no change feed: two-stage confirmation, append-only snapshot modelling, and cross-source corroboration, built around the fact that false positives cost far more than delay.

**Workflow automation across the stack.** Power Automate and Graph API tooling, lead enrichment pipelines (Apollo/HubSpot/Airtable), AI vision cost estimation deployed across 7 client sites, and document-processing automations.

---

## Repositories

| Repo | What it is |
|---|---|
| [multi-tenant-rag-architecture](https://github.com/Haris001-bit/multi-tenant-rag-architecture) | Design notes from a production RAG platform: retrieval, reranking, tenant isolation, latency tiering |
| [change-detection-pipeline-patterns](https://github.com/Haris001-bit/change-detection-pipeline-patterns) | Patterns for detecting state changes in systems you don't control |
| [multi-inbox-email-triage](https://github.com/Haris001-bit/multi-inbox-email-triage) | Email automation across nine shared inboxes: idempotency, thread identity, multi-label intent, never auto-send |
| [white-label-automation-architecture](https://github.com/Haris001-bit/white-label-automation-architecture) | One product, seven customer deployments: clone-per-tenant tradeoffs, config as data, vision estimation |
| [vision-document-extraction](https://github.com/Haris001-bit/vision-document-extraction) | Structured data out of layout-heavy documents: scatter-gather extraction, data contracts, entity matching |

*More in progress, including original tooling and further architecture write-ups.*

These are engineering write-ups rather than client deliverables. Client work is published only with written permission, and never includes source, credentials, or customer data. That's a standard I'd apply to your project too.

---

## Stack

**Automation** n8n · Make.com · Zapier · Power Automate
**Voice & conversational AI** Retell · Vapi · ElevenLabs · Voiceflow
**AI/LLM** OpenAI · Anthropic · RAG · hybrid retrieval · cross-encoder reranking · prompt engineering
**Data** PostgreSQL · Supabase · Airtable · MSSQL · web scraping · entity resolution
**Web** Next.js · React · TypeScript · .NET
**Integrations** Microsoft Graph · HubSpot · GoHighLevel · Jobber · Apollo · Twilio · Stripe

---

## How I work

**Documentation is part of the deliverable.** Every system I hand over comes with architecture docs explaining what it does, what's safe to change, and how to fix it at 2am. A system only one person understands isn't finished.

**Failure handling before features.** Retries, idempotency, rate-limit awareness and blast-radius caps get built in from the start. Automation that works on the happy path isn't automation, it's a demo.

**I'll tell you what won't work.** Including when the thing you asked for isn't the thing you need.

---

## Get in touch

Available for automation engineering, contract or full-time, remote.
