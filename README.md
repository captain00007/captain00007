# Georges Guy Gustinvil

**Software Engineer | Backend Architecture & Production AI Systems**  
Curitiba, PR, Brazil • [LinkedIn](https://www.linkedin.com/in/georges-guy-gustinvil-2a30bb56/) • [GitHub](https://github.com/captain00007)

---

### 💼 Engineering Overview

Software Engineer with a strong foundation in **Python, backend architecture, and distributed system design**, focusing on building **production-oriented AI applications and reliable retrieval systems**. 

Experienced in designing modular REST APIs, multi-tenant database architectures (PostgreSQL RLS), and document automation pipelines. Specializing in AI Engineering with an emphasis on **RAG pipelines, vector retrieval (pgvector), LLM security/guardrails, and automated evaluation systems**.

---

### 🛠️ Core Engineering Capabilities

```text
┌────────────────────────────────────────────────────────────────────────┐
│ BACKEND & SYSTEMS ARCHITECTURE                                         │
│ • Modular Monolith & Clean Architecture (Django, DRF)                  │
│ • Multi-Tenancy & Data Isolation (PostgreSQL Row-Level Security)       │
│ • RESTful API Design, Authentication (JWT), & RBAC                     │
│ • Background Processing, Workflow Automation & Document Ingestion      │
│ • Containerization & Parity (Docker, Docker Compose, Linux)            │
├────────────────────────────────────────────────────────────────────────┤
│ AI & LLM ENGINEERING                                                   │
│ • Production RAG Pipelines (Ingestion, Chunking, Embeddings, Hybrid)   │
│ • Vector Search & Persistence (PostgreSQL + pgvector)                  │
│ • LLM Security (Prompt Injection Mitigation, Canary Tokens, Guards)   │
│ • Rigorous Retrieval Whitelisting & Anti-Hallucination Constraints     │
│ • Automated Evaluation & Fidelity Testing (pytest-django, Groundedness)│
└────────────────────────────────────────────────────────────────────────┘
```

---

### 🚀 Featured Engineering Projects

#### 1. [MigrantIA — Production-Oriented RAG Platform](https://github.com/captain00007/migrantIA)
*An enterprise-grade, multi-lingual RAG system designed for strict legal and regulatory migration guidance.*
* **Architecture:** Decoupled business logic (`apps/`) and AI infrastructure (`ia/`).
* **Vector & Retrieval Engine:** Hybrid retrieval using PostgreSQL + `pgvector` paired with strict official-domain whitelist querying (Tavily).
* **AI Security & Guardrails:** Integrated prompt-injection filters, intent classifiers, canary token shields, and output sanitizers.
* **Reliability & Testing:** Automated evaluation framework (`pytest`) measuring retrieval groundedness and hallucination prevention.
* **Stack:** Python 3.12+, Django, DRF, PostgreSQL, pgvector, LangChain, Docker.

#### 2. [School SaaS — Multi-Tenant Educational Platform](https://github.com/captain00007/school-saas)
*A scalable multi-tenant management system built with native database isolation.*
* **Architecture:** Layered Service Architecture with domain isolation across academic, administrative, and financial modules.
* **Security & Multi-Tenancy:** Native PostgreSQL Row-Level Security (RLS) ensuring absolute tenant isolation at the database level.
* **Stack:** Python, Django REST Framework, Vue 3, Vite, PostgreSQL, Docker Compose.

#### 3. Document & Workflow Automation Systems
*Internal enterprise automation designed for legal and insurance workflows.*
* **Scope:** Document intake processing, timeline reconstruction, business-rule validation, and system integration.
* **Outcome:** Replaced repetitive manual data aggregation with automated, validated API and document pipelines.

---

### 🧰 Technical Stack

* **Backend & Systems:** Python, Django, Django REST Framework, PostgreSQL, Redis, Celery, Linux/Bash
* **AI Engineering:** RAG, Vector Search (`pgvector`), Embeddings, LLM Security / Guardrails, LangChain, Evaluation Suites
* **Data & Architecture:** Clean Architecture, Multi-Tenancy (RLS), Data Modeling, Relational Integrity, RESTful APIs
* **DevOps & Tooling:** Docker, Docker Compose, Git, GitHub Actions, Pytest, Postman
* **Frontend:** Vue.js 3, TypeScript, Tailwind CSS, Vite

---

### 📐 Engineering Principles

1. **System Reliability First:** AI should augment robust backend systems, not compensate for fragile architecture.
2. **Deterministic Guardrails:** High-stakes domains require strict retrieval boundaries, transparent citations, and verifiable fallbacks over unchecked generation.
3. **Reproducible Infrastructure:** Container parity across development and production environments with automated test coverage.
