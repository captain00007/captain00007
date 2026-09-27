# Georges Guy Gustinvil

**Software Engineer | Backend Architecture & Applied AI Systems**  
Curitiba, PR, Brazil • [LinkedIn](https://www.linkedin.com/in/georges-guy-gustinvil-2a30bb56/) • [GitHub](https://github.com/captain00007)

---

### 💼 Engineering Overview

Software Engineer with a solid foundation in **Python, backend architecture, and database design**, focusing on building **robust web applications, multi-tenant systems, and retrieval-augmented AI solutions (RAG)**.

Experienced in developing modular REST APIs with Django & DRF, implementing database isolation (PostgreSQL Row-Level Security), and designing data processing pipelines. Expanding into AI Engineering through practical implementations of **document ingestion, vector search with `pgvector`, embedding generation, and LLM orchestration**.

---

### 🛠️ Core Engineering Capabilities

```text
┌────────────────────────────────────────────────────────────────────────┐
│ BACKEND & SYSTEMS ARCHITECTURE                                         │
│ • Modular Monolith & Clean Architecture (Python, Django, DRF)          │
│ • Multi-Tenancy & Data Isolation (PostgreSQL Row-Level Security)       │
│ • RESTful API Design, JWT Authentication, & RBAC                       │
│ • Background Processing, Workflow Automation & Document Ingestion      │
│ • Containerization & Environment Parity (Docker, Docker Compose)       │
├────────────────────────────────────────────────────────────────────────┤
│ APPLIED AI & RETRIEVAL ENGINEERING                                     │
│ • RAG Pipelines (Document Ingestion, Text Cleaning, Chunking)          │
│ • Vector Storage & Similarity Search (PostgreSQL + pgvector)           │
│ • Embeddings & LLM Integration (LangChain, OpenAI API)                 │
│ • Multi-lingual Query Handling & Structured Information Retrieval      │
│ • Strict Source Whitelisting & Citation-based Responses                │
└────────────────────────────────────────────────────────────────────────┘
```

---

### 🚀 Featured Engineering Projects

#### 1. [MigrantIA — Multi-lingual RAG System](https://github.com/captain00007/migrantIA)
*A retrieval-augmented generation platform focused on legal and regulatory information for migrants.*
* **Architecture:** Clear separation between business domain logic (`apps/`) and AI/retrieval services (`ia/`).
* **Ingestion & Processing:** Custom pipeline for document loading, normalization, chunking, and metadata extraction.
* **Vector Retrieval:** Semantic search using PostgreSQL + `pgvector` alongside domain-specific filtering.
* **Multi-lingual Support:** Query processing and prompt templates supporting multiple languages.
* **Stack:** Python, Django, Django REST Framework, PostgreSQL, pgvector, LangChain, Docker.

#### 2. [School SaaS — Multi-Tenant Management Platform](https://github.com/captain00007/school-saas)
*A multi-tenant platform designed for academic and administrative management.*
* **Architecture:** Layered Service Architecture with domain isolation across academic, administrative, and user modules.
* **Multi-Tenancy:** Native PostgreSQL Row-Level Security (RLS) ensuring tenant data isolation at the database layer.
* **Full-Stack Integration:** REST API backend integrated with a responsive Vue 3 frontend.
* **Stack:** Python, Django REST Framework, Vue 3, Vite, PostgreSQL, Docker Compose.

#### 3. Document & Workflow Automation Systems
*Internal automation solutions for document intake and structured data extraction.*
* **Scope:** Document intake processing, timeline reconstruction, business rule validation, and system integration.
* **Outcome:** Replaced repetitive manual workflows with automated, validated API and document pipelines.

---

### 🧰 Technical Stack

* **Backend:** Python, Django, Django REST Framework, PostgreSQL, Redis, Celery, Linux/Bash
* **AI & Retrieval:** RAG, Vector Search (`pgvector`), Embeddings, LangChain, Document Ingestion Pipelines
* **Architecture & Data:** Clean Architecture, Multi-Tenancy (RLS), Data Modeling, RESTful APIs
* **DevOps & Tooling:** Docker, Docker Compose, Git, GitHub Actions, Pytest, Postman
* **Frontend:** Vue.js 3, TypeScript, Tailwind CSS, Vite

---

### 📐 Engineering Principles

1. **Solid Foundation First:** AI capabilities are built on top of reliable backend architecture, robust data modeling, and clean code.
2. **Verifiable Data Sources:** Prioritize deterministic retrieval, strict source filtering, and clear citations over unstructured generation.
3. **Environment Reproducibility:** Ensure consistent environments from local development to production using Docker.
