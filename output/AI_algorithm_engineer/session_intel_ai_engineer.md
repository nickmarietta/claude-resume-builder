# Session: Intel — AI Algorithm Engineer
## Status: Phase 0: DONE | Phase 1: DONE | Phase 2: Compile PENDING (user action required)

---

## JD Info
- **Company:** Intel Corporation
- **Role:** AI Algorithm Engineer (College Grad)
- **Locations:** Santa Clara, CA (primary) | Folsom, CA | Hillsboro, OR
- **Salary range:** $118,850 – $188,340 USD
- **Work model:** Hybrid
- **JD file:** `JDs/AI_algorithm_engineer.txt`
- **Output folder:** `output/AI_algorithm_engineer/`

---

## Requirements Table

| Requirement | Type | Nick's Coverage | Bridge/Note |
|-------------|------|----------------|-------------|
| B.S. CS/EE/CE | Minimum | **Direct** | CSUF CS, May 2026 |
| 3+ months Python | Minimum | **Direct** | EcoPrompt, EcoNauts, redClarity, SignalML (Expert) |
| 3+ months C++ | Minimum | Gap → Bridge | Config-declared + CS coursework; JD allows "academic coursework" |
| LangChain / LlamaIndex / AutoGen / HuggingFace | Preferred | **Gap** | No project evidence; acknowledge in CL only |
| RAG + vector databases (FAISS, Chroma) | Preferred | Bridge-HIGH | RAG = direct (EP-01, full system); vector DBs = gap |
| Prompt engineering + UX/UI | Preferred | **Direct** | CT-02 (Stockfish→NL), RC-02 (medical domain, 2 prompts) |
| Deploying AI agent platforms (local + cloud) | Preferred | Bridge-HIGH | EP-02 (Ollama local inference), RC (Cloud Run) |
| Building AI agents, chatbots, LLM apps | Preferred | **Direct** | CT (agentic/no-HITL), RC (LLM app), EP (RAG system) |
| Agent orchestration, tool usage | Preferred | Bridge-MED | Chess Tutor agentic design; no AutoGen/LangChain experience |
| Team environment / communication | Soft | **Direct** | EcoNauts (4-person, award), redClarity (team), EcoPrompt (3-person) |

**Coverage summary:** 5 Direct, 3 Bridge-HIGH, 1 Bridge-MED, 2 Gaps (LangChain ecosystem, vector DBs)

---

## ATS Keywords

**Must-include (exact JD terms):**
- generative AI, GenAI, AI agents, agent orchestration
- LLM, large language model, local LLM, cloud LLM
- RAG, retrieval-augmented generation
- prompt engineering
- Python, C++
- end-to-end development, production-quality software

**Bridge keywords (related, defensible):**
- local LLM inference (Ollama → Intel IPEX-LLM ecosystem)
- cloud deployment (Cloud Run → cloud LLM platform)
- agentic AI, no human-in-the-loop
- Gemini API (LLM API experience)
- FastAPI (AI service delivery)

**Avoid (no evidence):**
- LangChain, LlamaIndex, AutoGen, HuggingFace — do NOT use in bullets
- FAISS, Chroma, vector database — do NOT claim
- "orchestration framework" — not demonstrated

---

## Gap Assessment

| Gap | Bridge Available? | Confidence | Resolution |
|-----|-----------------|-----------|------------|
| C++ experience | YES — CS coursework; JD allows coursework | HIGH | List C++ in skills (config-declared); add "CS coursework" bridge in CL if needed |
| LangChain/LlamaIndex/AutoGen | Minimal bridge | LOW | Omit from bullets; mention "RAG systems foundational to these frameworks" in CL only |
| Vector databases (FAISS, Chroma) | Partial — PostgreSQL for persistence | LOW | Omit claim; focus on RAG pipeline architecture instead |
| Agent orchestration frameworks | Partial — agentic design from scratch | MED | Frame Chess Tutor as "custom agentic architecture" without claiming AutoGen |

---

## Company Context

**Mission:** Intel is positioning itself as the hardware and software layer enabling the AI era — processors, accelerators, and open-source tooling. The "One AI (1AI)" initiative is their internal agentic GenAI platform that consolidates siloed chatbots into orchestrated agents.

**Key Intel AI products relevant to this role:**
- **IPEX-LLM** — Intel's local LLM inference library; integrates with Ollama, HuggingFace, LangChain, LlamaIndex, and vLLM on Intel Arc/Xeon/NPU hardware
- **One AI (1AI)** — unified agentic GenAI platform for enterprise; target = orchestrated multi-agent systems replacing standalone chatbots
- **Intel Liftoff** — AI startup program enabling agentic solutions on Intel hardware

**Role purpose:** Building GenAI agents and platforms — this is an internal developer/tooling role building AI systems for Intel's own use cases, not a product engineering role for end customers. The engineer will work across local and cloud LLM deployment, RAG workflows, and agent orchestration.

**Intel-specific hooks:**
1. IPEX-LLM integrates with Ollama — Nick's EcoPrompt used Ollama for local inference — this is the exact ecosystem Intel is building for
2. Intel's One AI platform is about consolidating AI into orchestrated agents — Chess Tutor's agentic no-HITL design aligns with this vision
3. Intel values on-prem/local AI (it's their hardware differentiation) — EP-02's deliberate local inference choice resonates

**"Why Intel" angle:** Intel is at the intersection of hardware and AI software — building AI agents that run efficiently on-device (Intel Arc/NPU) rather than exclusively in the cloud. Nick's experience with local LLM inference (Ollama) and end-to-end AI pipeline construction positions him as someone who thinks about the full stack, not just the API call.

---

## Framing Strategy

**Lead narrative:** "Applied AI engineer who builds full-stack LLM pipelines, has shipped to real users, and thinks about local vs. cloud deployment tradeoffs — exactly what Intel's GenAI platform work requires."

**Primary frame:** GenAI agent builder — emphasize CT-01 (agentic no-HITL pipeline), EP-01 (RAG + local inference), RC-02 (prompt engineering). Never lead with SignalML for this JD — it's a ML/signals credential, not GenAI.

**Project priority for this JD:**
1. **EcoPrompt** (EP-01, EP-02) — RAG + Ollama local inference = strongest Intel match
2. **Chess Tutor** (CT-01, CT-02) — agentic AI design + prompt engineering
3. **redClarity** (RC-02, RC-05) — Gemini prompt engineering + two-call LLM architecture
4. **EcoNauts** (EN-01) — optional 4th; FastAPI ML serving + award = team delivery signal
5. SignalML — OMIT for this JD; ML/signals work, not GenAI agent work

**Emphasize:**
- RAG system (EP-01) — highest-value preferred qual match
- Local LLM inference (EP-02, Ollama) — direct Intel IPEX-LLM ecosystem hook
- Agentic design (CT-01) — "no human-in-the-loop" framing aligns with Intel One AI
- Prompt engineering in two domains (chess + medical) — shows adaptability

**Downplay / omit:**
- SignalML for this JD (no GenAI relevance; save for defense/research roles)
- Nuri / SwiftUI (mobile, not relevant)
- Docker/containerization (secondary for this JD)

**C++ gap handling:** List C++ in Technical Skills (it is in config). Do NOT fabricate project evidence. If CL mentions it: "C++ from CS coursework satisfies the 3-month minimum requirement as stated in the posting."

**Key metric to lead with:** 30% token reduction (HumanDelta) from EcoPrompt — only quantified AI efficiency metric in portfolio.

---

## Critique Context

**Reviewer persona:** Intel senior ML/AI engineer hiring for a college-grad GenAI role. Looking for: evidence of real LLM application building, understanding of RAG/agent concepts, Python fluency, willingness to learn new frameworks. NOT looking for: senior-level ownership, published research, clearance credentials.

**Competitive landscape:** Other applicants will have LangChain/HuggingFace experience from coursework or internships. Nick's differentiator is: end-to-end sole ownership (not tutorial projects), a measured outcome (30% token reduction), and real user deployment (Chess Tutor beta). These are stronger signals than framework familiarity.

**Domain vocabulary:** Use Intel's language — "local LLM inference," "agent orchestration," "RAG workflows," "LLM-powered applications," "end-to-end AI development." Avoid "agentic AI design" jargon unless mirroring JD language.

**Weaknesses to pre-empt:** LangChain gap is the biggest risk. Do NOT try to bridge it with a weak claim. Let RAG project speak for itself — it IS the underlying system that LangChain builds on top of.

---

## Cover Letter Plan

**Institution type:** Tech company (Intel — large enterprise, not startup)
**Tone:** Professional but conversational; enthusiastic about AI + Intel's hardware-software intersection
**Length:** 1 page, 250-300 words (Resume package)
**CL template:** `output/AI_algorithm_engineer/e2e_intel_ai_engineer_cover_letter.tex`

**Opening hook (use one of these):**
- "Intel's IPEX-LLM integrates with Ollama — the same local LLM runtime I used as the inference layer for my EcoPrompt RAG backend at FullyHacks 2026. When I saw this role, that connection made me stop scrolling."
- "My EcoPrompt backend runs a locally-hosted Ollama model instead of calling a cloud API — a deliberate choice that aligns directly with Intel's investment in on-device AI inference."

**Paragraph structure:**
1. Opening hook: Intel IPEX-LLM / Ollama connection → why this role specifically
2. RAG + LLM pipeline work: EP-01 (RAG system, 30% metric), CT-01 (agentic pipeline, real users)
3. Prompt engineering breadth: CT-02 + RC-02 (two domains, real constraints)
4. Team + delivery: EcoNauts award (team, FastAPI integration), CS degree May 2026
5. Close: Intel's local AI vision, my fit, call to action

**Jargon level:** Match JD's vocabulary — "generative AI agents," "retrieval-augmented workflows," "local and cloud-based LLMs," "end-to-end development"

**Avoid:** LangChain/HuggingFace gap; overstating C++ experience; claiming Nuri or SignalML relevance

---

## Bullet Plan (confirmed)

**Format:** 1-page resume | 6 bullets / 3 projects | All 2L

| Project | ID | Achievement | Variant | JD Match |
|---------|----|----|---------|----------|
| EcoPrompt — RAG Pipeline & Local LLM Inference | EP-01 | RAG backend + 30% token reduction (HumanDelta) | 2L | Direct |
| EcoPrompt — RAG Pipeline & Local LLM Inference | EP-02 | FastAPI→Ollama local inference, no cloud dependency | 2L | Bridge-HIGH |
| Chess Tutor — Agentic AI Coaching System | CT-01 | End-to-end agentic pipeline, real beta users | 2L | Direct |
| Chess Tutor — Agentic AI Coaching System | CT-02 | Prompt engineering: Stockfish→NL coaching | 2L | Direct |
| redClarity — LLM Prompt Engineering & Medical AI API | RC-02 | 2 Gemini system prompts, medical domain | 2L | Direct |
| redClarity — LLM Prompt Engineering & Medical AI API | RC-05 | Two-call Gemini architecture, atomic API response | 2L | Direct |

---

## Output Files
- Session: `output/AI_algorithm_engineer/session_intel_ai_engineer.md`
- Resume: `output/AI_algorithm_engineer/e2e_intel_ai_engineer_resume.tex` — WRITTEN, pending compile
- Cover Letter: `output/AI_algorithm_engineer/e2e_intel_ai_engineer_cover_letter.tex` — WRITTEN, pending compile

## Cover Letter Hooks Verified
- Intel IPEX-LLM integrates with Ollama — VERIFIED ✓ (github.com/intel/ipex-llm)
  - Note: repo archived Jan 28, 2026 (read-only); integration still valid/documented

## Next
- Resume: WRITTEN — pending user compile + GPA fill-in
- Cover Letter: WRITTEN — pending user compile
- Critique: PENDING → `/critique`
- Next (after compiling both): `/clear` then `/critique output/AI_algorithm_engineer/session_intel_ai_engineer.md`
