<h1 align="center">Juan Carlos Amay</h1>
<p align="center">
  <b>AI Architect & Senior Full Stack Engineer</b><br/>
  Claude Skills · MCP servers · RAG · AI agents · Java / Spring Boot · Node.js / NestJS · React
</p>
<p align="center">
  <a href="https://linkedin.com/in/juancarlosamayizquierdo"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:juancho6682@gmail.com"><img src="https://img.shields.io/badge/Email-juancho6682%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Location-Cuenca%2C%20Ecuador%20·%20Remote-2E7D32?style=for-the-badge" alt="Location"/>
  <img src="https://img.shields.io/badge/Open%20to-Full--time%20%2F%20Contract-6E40C9?style=for-the-badge" alt="Open to work"/>
</p>

---

I've spent 8+ years building secure, scalable backends for **fintech, banking and enterprise** clients. That work runs from core-banking migrations in Ecuador to multi-tenant digital banking platforms for the U.S. and LATAM.

Today I build **Applied AI in production**: agentic systems on **Anthropic Claude** and **OpenAI**, **Claude Skills**, **Model Context Protocol (MCP) servers**, **RAG pipelines** and **Playwright RPA agents**. For regulated industries I deploy them with a strict **human-in-the-loop** rule: no agent takes an irreversible action without a person's approval.

- 🧠 Currently: AI Architect at Singular Agency, building enterprise AI products for the U.S. market
- 🏦 Background: Java/Spring Boot and NestJS microservices with Kafka, CQRS, Saga, Outbox and idempotency
- 👥 Experience in international teams of 40+ engineers: PR governance, Clean Architecture/DDD, mentoring
- 🌎 Spanish (native) · English (B2–C1) · LATAM, U.S. and APAC time zones

## 🚀 Featured projects

> These are public reference implementations I wrote from scratch to show the patterns I use in production. They use fictional data, and client work stays private.

| Project | What it shows | Stack |
|---|---|---|
| [**mcp-practice-management-server**](https://github.com/Juankia/mcp-practice-management-server) | **B2B MCP server** that exposes a practice-management system (clients, matters, tasks, time) to AI agents. Auth stays server-side, writes go through a dry-run → confirm step, and creates are idempotent | TypeScript · MCP SDK · zod · vitest |
| [**mcp-food-ordering-server**](https://github.com/Juankia/mcp-food-ordering-server) | **B2C MCP server** that lets a consumer assistant browse menus, build a cart and order. Orders need a confirmation token, prices are recomputed on the server, and allergen warnings are surfaced | TypeScript · MCP SDK · vitest |
| [**claude-skills-hitl-automation**](https://github.com/Juankia/claude-skills-hitl-automation) | **Claude Agent Skills** (intake → drafting → filing prep) that share client state, plus a **Playwright RPA agent** with a mandatory human approval gate | Claude Skills · Python · Playwright · TypeScript |
| [**docsearch-ai-rag**](https://github.com/Juankia/docsearch-ai-rag) | **RAG document assistant** with pluggable vector stores (in-memory / Milvus), grounded answers with citations, stale-vector-safe re-ingestion and a retrieval eval harness | Python · FastAPI · LangChain · Milvus |
| [**multitenant-llm-gateway**](https://github.com/Juankia/multitenant-llm-gateway) | **Multi-tenant B2B LLM gateway** with per-tenant provider (OpenAI / Anthropic / Gemini / Ollama), fallback, circuit breaker, FinOps budgets (429 + reset header) and PostgreSQL **Row-Level Security** | NestJS · PostgreSQL (RLS) · TypeORM · Jest |
| [**fintech-transfers-saga**](https://github.com/Juankia/fintech-transfers-saga) | **Digital-bank transfer service**: orchestrated Saga with compensations, Transactional Outbox → Kafka, idempotency keys, risk scoring and hexagonal architecture | Java 17 · Spring Boot 3 · Kafka · Postgres |

## 🧰 Tech stack

**Applied AI**
![Claude](https://img.shields.io/badge/Anthropic%20Claude-191919?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-000000?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

**Backend**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data & Cloud**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## 💼 Experience

**AI Architect & Senior Full Stack Engineer** · *Singular Agency* · Remote, U.S. market · Feb 2026 – Present
- Shipped three production **Claude Skills** (client intake, legal document drafting, court-filing prep) that share client state and run on macOS and Windows.
- Built and deployed an **MCP server** that gives AI agents access to a practice-management platform. Its server-side authenticated pattern became an internal standard.
- Built a **Playwright RPA agent** for court e-filing. It reads credentials from the OS keychain and has a mandatory human approval gate.
- Designed the architecture of an end-to-end legal-workflow platform (4 phases, 19 user stories): Next.js + Vercel, Microsoft Entra ID / Graph, and Azure AI Document Intelligence for OCR.
- Shipped AI features on a Next.js + Supabase consumer app: a model-selection layer, AI reply suggestions and multi-environment RLS infrastructure.
- My engineering work was used as a case study for the company's Anthropic Claude Partner Network participation.

**Senior Full Stack Developer** · *SoFi / Technisys (Galileo)* · Remote · Oct 2024 – Feb 2026
- Built Java/Spring Boot and NestJS microservices for a multi-tenant LATAM digital-banking platform with 1,000+ concurrent users, using Clean Architecture, DDD and CQRS.
- Built Kafka flows for transfers, scoring and onboarding, with idempotency and Saga orchestration. Handled JWT/OAuth2 session security.
- Integrated the BioCatch behavioral fraud SDK, payment gateways and crypto operations on PCI-sensitive flows.
- Added DataDog observability and tuned PostgreSQL/Oracle. Owned PR governance and TDD, and mentored engineers in a team of 40+.

**Full Stack Engineer** · *WorkLlama* · Remote · Nov 2023 – Oct 2024
- Built NestJS services for an AI-driven workforce platform, including a **RAG chatbot** (OpenAI + Gemini) that pre-screens and shortlists candidates.
- Built React/Next.js SSR pages and ran Jest/Cypress in CI on AWS and GCP.

**Full Stack Developer** · *W2G Logistics (via BairesDev)* · Remote · Jun 2022 – Nov 2023
- Migrated legacy Java services to NestJS. Integrated ERP and 3PL platforms (Logiwa, Softeon) and built React dashboards on GCP.

**Backend Engineer / Scrum Master** · *TessPay Inc.* · Remote · Apr 2021 – Jun 2022
- Built payment and settlement APIs in Node.js and Spring Boot, with Adapter/Strategy layers for payment gateways, RBAC and AML/KYC support.

**IT Systems Coordinator / Team Lead** · *Cooperativa CREA* · Cuenca · Mar 2019 – Apr 2021
- Led 6 developers through a core-banking migration to Oracle Cloud Infrastructure. Built BPM automation for loans and onboarding, and integrated Equifax and Western Union.

**Backend Engineer** · *Cooperativa JEP* · Cuenca · Nov 2016 – Jun 2018
- Built account and credit modules, REST/SOAP APIs and ATM interfaces in Java and PHP.

**Independent Consultant** · *Freelance / AGROSERVIAL S.A.S.* · 2024 – Present
- Built DocSearch AI (RAG on FastAPI + Milvus, ~40% lower retrieval latency after migrating off Atlas Vector Search), an offline-first collections app (Flutter + Supabase + Angular) and utility-billing platforms.

## 🎓 Education

**Systems / Software Engineering** · Universidad Politécnica Salesiana, Cuenca, Ecuador

---

<p align="center"><i>Open to remote full-time or contract roles in AI engineering, backend and platform architecture. Get in touch on <a href="https://linkedin.com/in/juancarlosamayizquierdo">LinkedIn</a> or by <a href="mailto:juancho6682@gmail.com">email</a>.</i></p>
