<img src="https://github.com/alouani-youssef.png" alt="Youssef Alouani" width="120" align="right" />

# Youssef Alouani

**AI Engineer · Casablanca, Morocco**

I build AI that works on real data in production and keeps that data safe. I'm an AI engineer with a backend foundation: RAG and MCP over private data, Saudi-dialect speech, recommendations and privacy-aware assistants, evaluated before they ship.

[Portfolio](https://www.alouaniyoussef.com/) · [LinkedIn](https://www.linkedin.com/in/alouani-youssef) · [Medium](https://medium.com/@alouaniyoussef) · [Book a call](https://calendar.app.google/ru99z5cCrAbbu8LP9) · hello@youssefalouani.com

---

## Now

- Building **[Osoul](https://osoul.io)**: recommendation systems, reservations with deposits, and a privacy-aware AI assistant for fine-dining restaurants.
- Running **[10xJobs](https://10xjobs.vercel.app/)**, a cost-tuned pipeline on Apify actors that matches new job posts to each user's published profile.
- Maintaining **[AI Stones](https://github.com/alouani-youssef/stones)**, an AI harness of skills, guardrail hooks and settings for Claude Code.
- Writing about fine-tuning Whisper large-v3 for Saudi dialect.

## Experience

| Period | Role | Company |
|---|---|---|
| Jun 2026 – now | Technical Founder | [Osoul](https://osoul.io): Revenue-as-a-Service for fine dining |
| Feb 2024 – May 2026 | Lead Backend Engineer (founding, team of 9) | [Axelerated Solutions](https://www.alouaniyoussef.com/experience/axelerated) (Sowtek AXS) |
| Jul 2023 – Jan 2024 | Backend Engineer | [Finamaze](https://www.alouaniyoussef.com/experience/finamaze) |
| Dec 2021 – Jul 2023 | Software Engineer | [Qalqul Engine](https://www.alouaniyoussef.com/experience/qalqul) |

- **[Osoul](https://osoul.io)**: AI assistant with PII redaction and user auth propagation, recommendations and meal-completion promos, server-side CAPI ad signals, NFC/QR table sessions, reservations with deposits. Live in venues of [Barceló Group](https://www.barcelo.com) and [Atlas Group](https://atlashospitality.com).
- **[Axelerated Solutions](https://www.alouaniyoussef.com/experience/axelerated)**: fine-tuned Whisper large-v3 for Saudi dialect, the Customer Voice RAG pipeline with an MCP server as its retriever, an MCP server over backend APIs validated through Keycloak, and migrations to Kubernetes and hybrid deployments. Shipped to clients including [HRSD](https://www.hrsd.gov.sa) and [Tahreez](https://tahreez.com).
- **[Finamaze](https://www.alouaniyoussef.com/experience/finamaze)**: migrated a robo-advisor from B2C to multi-tenant B2B, with KYC (document and visual verification) and bank reconciliation, for [Saudi National Bank](https://www.alahli.com).
- **[Qalqul Engine](https://www.alouaniyoussef.com/experience/qalqul)**: NLP/NLU engines on language servers and Duckling, public chatbots and the Botpress v12 core, a stateless real-time platform with task dispatching, SDKs and chat widgets.

## Selected work

| Project | What it is | Result |
|---|---|---|
| [Saudi-dialect speech-to-text](https://www.alouaniyoussef.com/projects/saudi-stt) | Whisper large-v3 fine-tuned on WhatsApp and Asterisk audio, behind live transcripts and tool-using voice agents | WER **40% → 15%** on a held-out set |
| [Customer Voice](https://www.alouaniyoussef.com/projects/customer-voice) | RAG over structured data, documents and customer interactions, with an MCP retriever and auth, privacy and retention built in | **500k** calls processed per month |
| [Osoul platform](https://www.alouaniyoussef.com/projects/osoul) | Multi-tenant SaaS that turns the data restaurants usually lose into revenue KPIs | **+18%** average ticket, **−25%** no-shows |
| [Finamaze KYC](https://www.alouaniyoussef.com/projects/finamaze-kyc) | Investor onboarding with document and visual identity checks, plus reconciliation | **−60%** manual review time per file |

## Open source

| Project | Description |
|---|---|
| [AI Stones](https://github.com/alouani-youssef/stones) · [npm](https://www.npmjs.com/package/ai-stones) | An AI harness for Claude Code: Markdown skills, guardrail hooks and JSON settings, installed per project with `npx ai-stones init`. |
| [archio](https://github.com/alouani-youssef/archio) | Object storage in Go with a multi-node, high-availability cluster and semantic search over stored files, built on Docling. |
| [translator](https://github.com/alouani-youssef/translator) | Low-cost, context-aware translation: NLLB-200 for simple text, an LLM above a complexity threshold, behind a three-tier pgvector cache. |
| [tracker](https://github.com/alouani-youssef/tracker) · [tracking-sdk](https://github.com/alouani-youssef/tracking-sdk) | A Go/Gin user-recognition service and a TypeScript browser SDK, with every event HMAC-signed. Used in production. |
| [pg_inspector](https://github.com/alouani-youssef/pg_inspector) | An MCP server that gives AI assistants safe, read-only access to PostgreSQL. |

## What I work on

- **Agentic systems**: RAG with an MCP server as the retriever, and assistants that act with the user's own permissions, redact personal data and ask before they write.
- **NLP / conversational AI**: chatbots on Botpress, Rasa and an in-house engine; intent and entity extraction across Arabic, French and Darija.
- **Speech / ML**: Whisper fine-tuning, from audio preparation to evaluation.
- **Recommendation systems**: pairings, meal-completion promos and event-based dynamic pricing on one menu data model.
- **Data pipelines**: collect, clean, extract into type-safe LLM schemas and load.
- **Backend & platform**: multi-tenant SaaS, Kafka and RabbitMQ messaging, WebSockets, Keycloak, Kubernetes.

## Stack

- **Languages**: TypeScript, Python, Go, Kotlin
- **Backend**: NestJS, Node.js, FastAPI, FastAPI-MCP, Gin, TypeORM, gRPC
- **AI / LLM**: LangChain, LangGraph, RAG, MCP, embeddings, Ollama, DeepEval, Giskard
- **ML / NLP**: Whisper, fine-tuning, NLLB-200, zero-shot classification, Rasa, Botpress, Duckling
- **Data**: PostgreSQL, pgvector, Redis, Milvus, Docling
- **Messaging**: Kafka, RabbitMQ, WebSockets
- **Security**: Keycloak, OAuth2/OIDC, PII redaction, HMAC signing, data privacy and retention
- **Infra**: Kubernetes, Docker Compose, Ansible, Nginx, hybrid deployments
- **Frontend**: React, Next.js, React Native

## Writing

- [Apache Kafka: all I know](https://alouani-youssef.medium.com/apache-kafka-all-what-i-know-71babb86a9ac)
- [RabbitMQ: how it works under the hood](https://alouani-youssef.medium.com/rabbitmq-understand-how-it-works-under-the-hood-895b74c37f3b)
- [The Full Path into the API Gateway](https://alouani-youssef.medium.com/the-full-path-into-the-api-gateway-f3285c96d627)
- [A Vision about Software Architecture Styles](https://alouani-youssef.medium.com/a-vision-about-software-architcture-styles-3ec0666b692c)
- [The Philosophy Behind Virtualization and Containerization](https://alouaniyoussef.medium.com/the-philosophy-behind-virtualization-and-containerization-c13866d74ed5)

More on [alouaniyoussef.com](https://www.alouaniyoussef.com/) and [Medium](https://medium.com/@alouaniyoussef).

---

English · French · Arabic. Open to backend and AI engineering roles, remote or in Casablanca.
