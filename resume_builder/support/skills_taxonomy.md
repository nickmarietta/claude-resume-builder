---
name: skills_taxonomy
description: Categorized skills inventory derived from all 5 project extractions + config.md declared skills
metadata:
  type: support
---

# Skills Taxonomy

## Summary Stats
- Total unique skills: 38
- Project evidence: 5 projects (Chess Tutor, EcoPrompt, EcoNauts, Nuri, redClarity)
- No academic publications — all evidence is project-based
- Top demonstrated skills: Python, FastAPI, Flask, Prompt Engineering, RAG, SwiftUI, Docker

---

## Category 1: Languages & Runtimes

| Skill | Proficiency | Evidence | Resume Weight |
|-------|-------------|----------|---------------|
| Python | Expert | EcoPrompt (sole backend), EcoNauts (FastAPI layer), redClarity (sole backend) | HIGH |
| TypeScript | Expert | Chess Tutor (sole, full stack, 26.9% of repo) | HIGH |
| Swift | Proficient | Nuri (~15 screens, full SwiftUI logic layer) | MED |
| JavaScript | Familiar | Config declared; React contribution in EcoNauts | MED |
| C++ | Familiar | Config declared; no project evidence | LOW |
| Java | Familiar | Config declared; no project evidence | LOW |
| HTML | Familiar | Chess Tutor (72.8% of repo — mostly structure) | LOW |

**Notes:**
- Python and TypeScript are the two strongest language claims — multiple sole-owner projects each
- Swift is a differentiator (only mobile project); use when JD mentions iOS or mobile
- C++ and Java are declared skills with no project evidence; list on resume but do not lead with them

---

## Category 2: AI/ML & LLM

| Skill | Proficiency | Evidence | Resume Weight |
|-------|-------------|----------|---------------|
| Prompt Engineering | Expert | Chess Tutor (CT-02: engine→NL translation), redClarity (RC-02: 2 medical system prompts) | HIGH |
| LLM Integration | Expert | Chess Tutor (pipeline), redClarity (2-call Gemini architecture) | HIGH |
| RAG (Retrieval-Augmented Generation) | Proficient | EcoPrompt (EP-01: sole-built RAG system, 30% token reduction) | HIGH |
| Gemini API | Proficient | redClarity (RC-02, RC-05: 2 system prompts, sequential calls) | HIGH |
| Agentic AI Design | Proficient | Chess Tutor (CT-01: no-HITL pipeline, PGN→Stockfish→LLM) | MED |
| Local LLM Inference (Ollama) | Proficient | EcoPrompt (EP-02: qwen2.5:1.5b, local inference pipeline) | MED |
| Stockfish Integration | Familiar | Chess Tutor (CT-04: WASM integration) | MED |
| WebAssembly (WASM) | Familiar | Chess Tutor (CT-04: async resolution) | LOW |
| TensorFlow | Familiar | Config declared; EcoNauts ML models were teammates' | LOW |
| scikit-learn | Familiar | Config declared; EcoNauts RF model was teammates' | LOW |
| NumPy | Familiar | Config declared; no first-party project evidence | LOW |

**Notes:**
- Prompt engineering and LLM integration are Nick's strongest AI claims — two separate projects, different domains (chess + medical)
- RAG is high-value for ML/AI Engineer roles; EP-01 is the anchor
- Do NOT claim TensorFlow or scikit-learn as primary skills — EcoNauts models were teammates'; these are config-declared only

---

## Category 3: Web Frameworks & APIs

| Skill | Proficiency | Evidence | Resume Weight |
|-------|-------------|----------|---------------|
| FastAPI | Expert | EcoPrompt (EP-01→05: sole backend), EcoNauts (EN-01: sole routing layer) | HIGH |
| Flask | Expert | redClarity (RC-01→05: sole backend, 7 endpoints) | HIGH |
| REST API Design | Expert | redClarity (7 endpoints), EcoPrompt (FastAPI), EcoNauts (FastAPI) | HIGH |
| React | Familiar | EcoNauts (EN-03: contributing, metric display UI) | MED |
| SwiftUI | Proficient | Nuri (NU-01→04: ~15 screens, data binding, navigation, state) | MED |
| Next.js | Familiar | Config declared; EcoPrompt frontend was teammates' | LOW |
| SvelteKit | Familiar | Config declared; redClarity frontend was teammates' | LOW |
| Node.js | Familiar | Config declared; no first-party project evidence | LOW |
| Flask-CORS | Familiar | redClarity (RC-01: Svelte integration) | LOW |

**Notes:**
- FastAPI and Flask are peer-level expert skills — Nick sole-owned backends in both frameworks
- React is a supporting claim only: contributing role in EcoNauts metric UI. Do not claim "built in React" for any project
- Next.js/SvelteKit: teammates' frameworks — list as declared skills, do not include in bullet text

---

## Category 4: Data & Databases

| Skill | Proficiency | Evidence | Resume Weight |
|-------|-------------|----------|---------------|
| PostgreSQL | Proficient | EcoPrompt (EP-04: schema design, Neon deployment) | MED |
| PyPDF2 / PDF Parsing | Familiar | redClarity (RC-04: CMP header-split strategy) | LOW |
| Google Cloud Translate API | Familiar | redClarity (RC-03: 4-language output) | MED |

---

## Category 5: DevOps & Cloud

| Skill | Proficiency | Evidence | Resume Weight |
|-------|-------------|----------|---------------|
| Docker | Proficient | EcoNauts (EN-02: docker-compose.yml sole authorship) | HIGH |
| Docker Compose | Proficient | EcoNauts (EN-02: cross-container networking, multi-service) | HIGH |
| Google Cloud Platform (GCP) | Familiar | redClarity (Cloud Run deployment, Cloud Translate API) | MED |
| Git | Proficient | All projects (36 commits in redClarity backend; implied across all) | MED |
| AWS | Familiar | Config declared; no project evidence | LOW |
| Google Cloud Run | Familiar | redClarity (inferred from PORT env var pattern) | LOW |

---

## Category 6: Mobile

| Skill | Proficiency | Evidence | Resume Weight |
|-------|-------------|----------|---------------|
| iOS Development | Proficient | Nuri (~15 SwiftUI screens, full app logic layer) | MED |
| SwiftUI | Proficient | Nuri (data binding, navigation, state across full app) | MED |
| Figma Handoff | Proficient | Nuri (sole design-to-code bridge, all screens) | MED |

---

## Category 7: Tools & Evaluation Frameworks

| Skill | Proficiency | Evidence | Resume Weight |
|-------|-------------|----------|---------------|
| Stockfish (chess engine) | Familiar | Chess Tutor (WASM integration) | MED |
| HumanDelta | Familiar | EcoPrompt (evaluation framework, source of 30% metric) | LOW |
| Mapbox GL JS | Familiar | EcoNauts (coordinate validation, contributing) | LOW |
| Recharts | Familiar | EcoNauts (metric display UI, contributing) | LOW |

---

## Skills vs. config.md Cross-Reference

The config.md Skills Reference table defines the 20 fixed resume skills. All of these are declarable; the table below flags which have strong project evidence vs. config-declared-only.

| Config Skill | Evidence Level | Notes |
|-------------|---------------|-------|
| Python | Strong (multiple projects) | Lead skill |
| JavaScript | Weak (contributing) | Config-declared |
| TypeScript | Strong (Chess Tutor, sole) | Lead skill |
| C++ | Config-declared only | No project evidence |
| Java | Config-declared only | No project evidence |
| TensorFlow | Config-declared only | EcoNauts ML was teammates' |
| NumPy | Config-declared only | No first-party evidence |
| Gemini API | Strong (redClarity) | 2 system prompts, sequential calls |
| scikit-learn | Config-declared only | EcoNauts RF was teammates' |
| React | Weak (contributing) | EcoNauts metric UI only |
| Next.js | Config-declared only | Teammates' framework |
| SvelteKit | Config-declared only | Teammates' framework |
| Flask | Strong (redClarity, sole) | Lead skill |
| FastAPI | Strong (EcoPrompt + EcoNauts, sole) | Lead skill |
| Node.js | Config-declared only | No first-party evidence |
| Git | Implied across all projects | Safe to list |
| Docker | Strong (EcoNauts, sole compose) | Lead skill |
| Google Cloud Platform | Moderate (Cloud Run, Translate) | Supporting |
| AWS | Config-declared only | No project evidence |
| PostgreSQL | Moderate (EcoPrompt schema) | Supporting |
