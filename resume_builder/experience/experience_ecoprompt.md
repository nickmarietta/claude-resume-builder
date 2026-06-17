---
name: experience_ecoprompt
description: EcoPrompt hackathon project — Nick built full backend (RAG, FastAPI, Ollama, HumanDelta, PostgreSQL); 30% token reduction; FullyHacks 2026, no award
metadata:
  type: experience
---

# Experience: EcoPrompt — AI Prompt Optimizer
## 2026 — Team Hackathon Project (3 people), FullyHacks 2026

### Cross-Project Section
EcoPrompt is Nick's strongest demonstration of backend RAG engineering under time pressure. He sole-built the entire backend — RAG system, FastAPI→Ollama pipeline, HumanDelta evaluation integration, and PostgreSQL schema — while teammates handled the Next.js frontend. The 30% token reduction metric (HumanDelta output) is the project's anchor number and the only verifiable metric; it should always accompany the RAG/backend framing.

**CL framing:** Use EcoPrompt to show RAG system implementation, local LLM deployment experience (Ollama), and the ability to own an entire backend layer on a cross-functional team. The sustainability angle (token efficiency = reduced compute energy) is a differentiating hook for companies with green engineering goals.

**Correct framing reminder:** "no award" — never imply hackathon placement.

---

### Achievement EP-01: RAG-Powered Prompt Rewriting Backend
**Source:** marietta2025_ecoprompt.md
**Paper:** N/A — hackathon project
**User's role:** Sole backend contributor (RAG system, FastAPI, Ollama, HumanDelta, PostgreSQL)
**Status:** Hackathon submission — no award

**Context:** Token-heavy prompts increase cost and environmental impact. EcoPrompt rewrites user prompts via a RAG-augmented local LLM to reduce token count without sacrificing output quality, measured against HumanDelta's scoring framework.

**Bullet variants:**
- **2L:** Built a RAG-powered prompt rewriting backend in FastAPI, integrating a locally-run Ollama LLM to optimize user prompts and deliver a measured 30% reduction in token usage as scored by HumanDelta.
- **3L:** Architected and sole-built a Retrieval-Augmented Generation (RAG) prompt rewriting backend in FastAPI, integrating a locally-run Ollama `qwen2.5:1.5b` model to rewrite user prompts for efficiency, achieving a 30% measured reduction in token usage as quantified by the HumanDelta evaluation framework at FullyHacks 2026.
- **1L:** Built RAG-powered FastAPI backend with local Ollama LLM; achieved 30% token reduction via HumanDelta scoring.

**Key skills:** RAG, FastAPI, Ollama, local LLM inference, prompt optimization, Python
**ATS keywords:** RAG, retrieval-augmented generation, FastAPI, Ollama, LLM, token efficiency, prompt optimization
**Reframing notes:** ML/AI — lead with RAG and local inference architecture. Full Stack — lead with FastAPI backend ownership and 3-service demo delivery. Defense — low unless JD mentions AI efficiency or cost reduction.

---

### Achievement EP-02: FastAPI → Ollama Local Inference Pipeline
**Source:** marietta2025_ecoprompt.md
**Paper:** N/A — hackathon project
**User's role:** Sole backend contributor
**Status:** Hackathon submission — no award

**Context:** Using a locally-run LLM (Ollama) instead of a cloud API eliminates latency and external dependency during a live demo — a deliberate engineering decision, not a cost-saving shortcut.

**Bullet variants:**
- **2L:** Designed and wired the FastAPI → Ollama inference pipeline using a locally-run `qwen2.5:1.5b` model, eliminating cloud API dependency and latency for reliable live hackathon demo conditions.
- **3L:** Designed and wired a FastAPI → Ollama inference pipeline using `qwen2.5:1.5b` running entirely locally, deliberately routing all LLM inference through a local process to eliminate cloud API latency and external dependency during live hackathon demo conditions, ensuring demo reliability under network constraints.
- **1L:** Wired FastAPI → Ollama pipeline for local LLM inference, removing cloud API dependency during demo.

**Key skills:** FastAPI, Ollama, local LLM, Python, API design, inference pipeline
**ATS keywords:** FastAPI, Ollama, local inference, LLM pipeline, API, Python
**Reframing notes:** ML/AI — emphasize local inference architecture decision. Full Stack — emphasize backend service wiring. Defense — relevant if JD mentions on-premise or air-gapped AI.

---

### Achievement EP-03: HumanDelta Evaluation Integration
**Source:** marietta2025_ecoprompt.md
**Paper:** N/A — hackathon project
**User's role:** Sole backend contributor
**Status:** Hackathon submission — no award

**Context:** A prompt optimizer without a measurement layer produces unverifiable claims. Integrating HumanDelta as the scoring framework gives the system a real evaluation pipeline and produces the 30% token reduction figure as a measurable, reproducible output.

**Bullet variants:**
- **2L:** Integrated the HumanDelta evaluation framework to produce real-time environmental impact scores alongside rewritten prompts, surfacing the 30% token reduction metric as a quantified system output.
- **3L:** Integrated HumanDelta as an evaluation layer within the backend pipeline, scoring prompt rewrites in real time and rendering environmental impact metrics alongside each optimized prompt — producing the 30% token reduction figure as a measured, reproducible output of the full RAG system.
- **1L:** Integrated HumanDelta scoring to surface real-time environmental impact metrics per rewritten prompt.

**Key skills:** HumanDelta, evaluation frameworks, metrics pipeline, Python, FastAPI
**ATS keywords:** evaluation framework, metrics, token reduction, environmental impact, AI efficiency
**Reframing notes:** ML/AI — secondary to EP-01; use as supporting metric. Full Stack — mention as evaluation layer. Defense — omit unless sustainability is in JD.

---

### Achievement EP-04: PostgreSQL Schema for Prompt History
**Source:** marietta2025_ecoprompt.md
**Paper:** N/A — hackathon project
**User's role:** Sole backend contributor
**Status:** Hackathon submission — no award

**Context:** Persisting prompt history and before/after comparisons enables replay, metric verification, and longitudinal analysis — turning a demo into a system with an audit trail.

**Bullet variants:**
- **2L:** Designed the PostgreSQL (Neon) schema for persistent prompt history and before/after comparison storage, enabling metric replay and verification across the three-service backend architecture.
- **3L:** Designed and implemented a PostgreSQL database schema via Neon to persist prompt histories and store before/after comparison records for each rewrite request, supporting real-time scoring display and retroactive metric verification across the three-service architecture (Ollama, FastAPI, Next.js).
- **1L:** Set up PostgreSQL schema for persistent prompt history and before/after comparison tracking.

**Key skills:** PostgreSQL, Neon, database design, schema design, Python
**ATS keywords:** PostgreSQL, database design, Neon, backend, data persistence
**Reframing notes:** Full Stack — strongest fit (database design). ML/AI — secondary. Defense — omit.

---

### Achievement EP-05: End-to-End Hackathon Backend Delivery
**Source:** marietta2025_ecoprompt.md
**Paper:** N/A — hackathon project
**User's role:** Sole backend contributor; team of 3 overall
**Status:** Hackathon submission — no award

**Context:** Delivering a working 3-service demo (Ollama + FastAPI + Next.js) at hackathon speed, coordinating with teammates building the frontend, shows execution ability under pressure. Use only as a supporting or framing bullet — EP-01 is the lead.

**Bullet variants:**
- **2L:** Contributed backend and LLM infrastructure for an AI sustainability tool demoed at FullyHacks 2026, coordinating a 3-service architecture (Ollama, FastAPI, Next.js) with a 3-person team within hackathon time constraints.
- **3L:** Sole-built backend (RAG pipeline, FastAPI, Ollama, HumanDelta, PostgreSQL) and coordinated integration with a teammate-built Next.js frontend to deliver a working AI sustainability tool demo at FullyHacks 2026, managing a 3-service architecture under hackathon constraints.
- **1L:** Delivered full RAG backend for a 3-service AI tool at FullyHacks 2026 hackathon on a 3-person team.

**Key skills:** Team coordination, rapid delivery, full-stack integration, hackathon execution
**ATS keywords:** hackathon, team collaboration, full-stack, rapid prototyping
**Reframing notes:** Use sparingly — EP-01 supersedes this. Merge into EP-01 framing when space is tight.

---

### Provenance Guardrails (All EP Achievements)
- NO award — never imply placement at FullyHacks 2026
- 30% token reduction is a HumanDelta output — safe to claim; do not inflect it beyond "as measured by HumanDelta"
- Do not claim frontend work — teammates built Next.js/React/Tailwind
- Nick's ownership: backend only (RAG, FastAPI, Ollama, HumanDelta, PostgreSQL)
