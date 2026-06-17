---
name: achievement_reframing_guide
description: Per-achievement significance + role-type priority mapping for ML/AI Engineer, Full Stack Engineer, and Defense/Aerospace
metadata:
  type: support
---

# Achievement Reframing Guide

## How to Use
Each entry has a `Significance` line (why this matters broadly) and a role-type table showing priority, lead verb, and framing angle per audience. Use this guide to select and frame bullets for any JD before generating.

**Role types:** ML/AI Engineer | Full Stack Engineer | Defense/Aerospace

**Priority levels:** HIGH = lead bullet candidate | MED = supporting bullet | LOW = omit unless space/JD demands

---

## CHESS TUTOR

### CT-01: End-to-End AI Coaching Pipeline
**Significance:** Demonstrates ability to design and ship a complete agentic AI product — search-based engine + generative AI + user interface — without a team.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | HIGH | Built | Lead with "agentic AI" and "no human-in-the-loop." Emphasize bridging Stockfish (search-based) with LLM (generative) as a design choice. |
| Full Stack Engineer | MED | Architected | Lead with pipeline architecture and end-to-end delivery. Emphasize that it serves real beta users. |
| Defense/Aerospace | LOW | — | Omit unless JD specifically mentions AI integration or autonomous systems. |

**Overclaiming warning:** None — sole contributor on all claims.
**First-pass checklist:** [x] Verb matches role (sole) [x] "beta with real users" — not "deployed" or "production" [x] No user count stated

---

### CT-02: Prompt Engineering for Engine-to-Language Translation
**Significance:** Prompt engineering with a real constraint — the input (Stockfish output) is structured and numerical, and the output must be pedagogically useful, not just grammatically correct.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | HIGH | Engineered | Lead with "bridging search-based and generative AI." Frame as an NL interface design challenge, not just "wrote prompts." |
| Full Stack Engineer | MED | Engineered | Secondary to CT-03/CT-04. Mention as LLM API use case if budget allows. |
| Defense/Aerospace | LOW | — | Omit. |

**Overclaiming warning:** None — sole contributor.
**First-pass checklist:** [x] Verb correct [x] "centipawn scores" and "best-move sequences" are accurate technical terms from Stockfish

---

### CT-03: Interactive Board UI + Session History Model
**Significance:** Shows product thinking — the session history model was built for future value (habit tracking), not just current functionality.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | LOW | — | Omit. UI/state management is not ML/AI. |
| Full Stack Engineer | HIGH | Designed | Lead with frontend engineering + data modeling. Emphasize move-by-move navigation as a UX feature built for a specific user need. |
| Defense/Aerospace | LOW | — | Omit. |

**First-pass checklist:** [x] Verb correct [x] "beta" framing applies to all CT bullets

---

### CT-04: Stockfish WASM Integration
**Significance:** Solving async evaluation constraints in a WASM browser context is a non-trivial engineering problem — demonstrates ability to debug and resolve runtime constraints.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Integrated | Use as supporting detail for CT-01. Mention WASM as the delivery mechanism. |
| Full Stack Engineer | HIGH | Integrated | Lead with the browser engineering challenge and async resolution. This is the strongest "solved a hard problem" signal in Chess Tutor for FS. |
| Defense/Aerospace | LOW | — | Omit. |

---

### CT-05: v1 Release + User Feedback Iteration
**Significance:** Full product lifecycle ownership — the only project where Nick shipped, observed real user behavior, and iterated.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Shipped | Use as closing bullet for Chess Tutor to signal product instinct. "Iterated on LLM explanation quality" is the AI-specific hook. |
| Full Stack Engineer | MED | Shipped | Same as ML/AI. Good closing bullet. |
| Defense/Aerospace | LOW | — | Omit. |

---

## ECOPROMPT

### EP-01: RAG-Powered Prompt Rewriting Backend
**Significance:** RAG system implementation with a measurable outcome (30% token reduction) — the strongest single quantified result in the entire portfolio.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | HIGH | Built | Lead with RAG and local inference. The 30% metric must appear. Frame as an AI efficiency system, not just a backend. |
| Full Stack Engineer | HIGH | Built | Lead with backend sole-ownership and 30% metric. Frame as full backend delivery for an AI tool. |
| Defense/Aerospace | MED | Built | Use if JD mentions AI efficiency, on-prem AI, or cost reduction. Lead with "local inference" angle (Ollama = no cloud dependency). |

**Overclaiming warning:** "30% token reduction" is a HumanDelta output — safe to claim as measured. Do not say "30% performance improvement" or generalize beyond token usage.
**First-pass checklist:** [x] "as measured by HumanDelta" or equivalent qualifier [x] "no award" framing for FullyHacks 2026 [x] Do not claim frontend

---

### EP-02: FastAPI → Ollama Local Inference Pipeline
**Significance:** Deliberate local-inference architecture — demonstrates knowledge of LLM deployment tradeoffs (cloud vs. local) and ability to act on them.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | HIGH | Designed | Emphasize the architectural decision: local inference chosen deliberately to eliminate cloud dependency. Frame as LLM deployment knowledge. |
| Full Stack Engineer | HIGH | Wired | Emphasize backend service-to-service integration. |
| Defense/Aerospace | MED | Designed | "No cloud dependency" maps to air-gapped / on-prem AI deployment context in defense. Use if JD mentions on-prem or air-gapped systems. |

---

### EP-03: HumanDelta Evaluation Integration
**Significance:** Demonstrates ability to integrate third-party evaluation frameworks — a data engineering skill relevant to MLOps and AI quality pipelines.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Integrated | Use as supporting detail for EP-01. Provides the "how we measured 30%" context. |
| Full Stack Engineer | MED | Integrated | Secondary to EP-01. Mention if space allows. |
| Defense/Aerospace | LOW | — | Omit. |

---

### EP-04: PostgreSQL Schema for Prompt History
**Significance:** Schema design for a multi-service backend — shows database thinking beyond just "connected to a DB."

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | LOW | — | Omit. Database work is secondary to the AI pipeline story. |
| Full Stack Engineer | HIGH | Designed | Full Stack lead bullet for EcoPrompt if EP-01 is the AI bullet. Show database ownership alongside backend. |
| Defense/Aerospace | LOW | — | Omit. |

---

### EP-05: End-to-End Hackathon Delivery
**Significance:** Weakest standalone claim — use only as context or merge into EP-01 framing.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | LOW | — | Merge into EP-01 framing. |
| Full Stack Engineer | LOW | — | Merge into EP-01 framing. |
| Defense/Aerospace | LOW | — | Omit. |

---

## ECONAUTS

### EN-01: FastAPI Routing Layer (ML → Frontend)
**Significance:** ML model serving — took two production-quality ML model outputs and made them consumable by a frontend via a clean API. The 1st place award is the social proof.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | HIGH | Built | Lead with "ML model serving" framing. Emphasize that this is the layer that made the ML outputs accessible. Always include the 1st place result. |
| Full Stack Engineer | HIGH | Built | Lead with API layer sole-ownership and the award. Frame as backend integration anchor for the project. |
| Defense/Aerospace | MED | Built | Frame as systems integration (ML outputs → REST API → frontend). Mention 1st place. |

**Overclaiming warning:** Do NOT claim the ML models (RF, ANN) — those were teammates'. Correct framing: "connecting ML model outputs" not "building the ML models."
**First-pass checklist:** [x] "team of 4" attribution on award [x] "FastAPI routing layer" is sole ownership [x] ML models not claimed

---

### EN-02: Docker Compose Orchestration
**Significance:** Container orchestration for a multi-service system — demonstrates DevOps fundamentals relevant to any team that ships software.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | LOW | — | Omit unless JD mentions MLOps or containerization. Infrastructure secondary to AI claims. |
| Full Stack Engineer | HIGH | Wrote | Use as DevOps/infrastructure bullet for EcoNauts. Pair with EN-01 for a complete project picture. |
| Defense/Aerospace | HIGH | Wrote | Docker/containerization is highly relevant to defense software stacks. Lead with "multi-service architecture" and "reliable startup sequencing." |

---

### EN-03: Frontend Metric Display UI (Contributing)
**Significance:** React data visualization and Mapbox coordinate validation — shows frontend breadth but is a contributing role.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | LOW | — | Omit. |
| Full Stack Engineer | MED | Contributed | Include as supporting bullet to show frontend breadth. MUST use "contributed to" — not "built." |
| Defense/Aerospace | LOW | — | Omit. |

**Overclaiming warning:** ALWAYS hedge — "contributed to" not "built." Primary frontend was a teammate.

---

### EN-04: 1st Place Award + Integration Summary
**Significance:** Team award from a named competition — strongest social-proof signal in the portfolio.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Helped deliver | Use as project header/summary bullet for EcoNauts. Combine with EN-01 for the technical anchor. |
| Full Stack Engineer | MED | Helped deliver | Same as ML/AI. |
| Defense/Aerospace | LOW | — | Omit as standalone; the award can appear as parenthetical in EN-01. |

**Note:** EN-04 is a framing bullet, not a standalone technical achievement. Always pair with EN-01 or EN-02 as the technical anchor.

---

## NURI

### NU-01: ~15 SwiftUI Screens from Figma
**Significance:** Full app UI implementation from design specs — demonstrates mobile engineering breadth and design handoff capability.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | LOW | — | Omit. No AI component. |
| Full Stack Engineer | HIGH | Implemented | Lead bullet for Nuri. Emphasize scale (~15 screens) and Figma handoff process. |
| Defense/Aerospace | LOW | — | Omit unless JD mentions mobile or iOS. |

---

### NU-02: Recommendation System Integration
**Significance:** UI integration with a backend recommendation system — shows ability to consume and surface ML-adjacent outputs in a user interface.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Integrated | Frame as "wired UI to recommendation system outputs" — do not claim the algorithm. Use if JD mentions recommendation systems or personalization. |
| Full Stack Engineer | HIGH | Integrated | Strong supporting bullet for Nuri — shows full-stack integration (UI ↔ recommendation backend ↔ database). |
| Defense/Aerospace | LOW | — | Omit. |

**Overclaiming warning:** Do NOT use "built" or "designed" for the recommendation system. Nick integrated the SwiftUI views to its outputs. Correct verbs: integrated, connected, wired.

---

### NU-03: Skincare Product Database Integration
**Significance:** SwiftUI data layer connecting views to database queries — real-time filtering and lookup through live database integration.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | LOW | — | Omit. |
| Full Stack Engineer | HIGH | Connected | Use as data layer bullet for Nuri. Pairs well with NU-01 to show full UI→data integration story. |
| Defense/Aerospace | LOW | — | Omit. |

**Overclaiming warning:** Do NOT claim database schema/construction — teammates built it. Nick connected SwiftUI views to it.

---

### NU-04: Sole Design-to-Code Bridge
**Significance:** On a 4-person team, Nick was the only engineer responsible for converting all designs into working code — demonstrates both technical execution and Figma workflow fluency.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | LOW | — | Omit. |
| Full Stack Engineer | HIGH | Served as | Strong team context bullet for Nuri. Frames Nick's unique contribution on a cross-functional team. |
| Defense/Aerospace | LOW | — | Omit. |

---

## REDCLARITY

### RC-01: 7-Endpoint Flask REST Backend
**Significance:** Sole ownership of a production-structured API serving a medical domain — the fullest backend ownership in the portfolio.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Built | Use as supporting context for RC-02 (the prompt engineering is the AI story; the backend is the delivery layer). |
| Full Stack Engineer | HIGH | Built | Lead bullet for redClarity. 7 endpoints, sole ownership, medical domain = strong differentiation. |
| Defense/Aerospace | MED | Built | Frame as "architected REST API for [domain] system." Backend engineering skills transfer. |

**Overclaiming warning:** "contributed backend and LLM layer" when referring to the whole product — do not claim the Svelte frontend. "Built for BeachHacks" — never imply award.

---

### RC-02: Gemini Prompt Engineering — Medical Domain
**Significance:** Two-prompt medical AI system where accuracy and plain-language accessibility are in direct tension — the most domain-specific prompt engineering in the portfolio.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | HIGH | Engineered | Lead bullet for redClarity. Emphasize medical domain, the two-prompt architecture, and the explanation+questions output pair. Frame as applied LLM engineering with real-world consequence. |
| Full Stack Engineer | MED | Engineered | Secondary to RC-01. Mention as LLM integration differentiator. |
| Defense/Aerospace | MED | Engineered | Frame as "NLP/AI applied to a document analysis problem" — parallels document intelligence use cases in defense. |

---

### RC-03: Google Cloud Translate — 4-Language Accessibility
**Significance:** Multilingual output via Cloud API — demonstrates cloud API integration and accessibility-aware engineering.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | LOW | — | Omit. API integration is secondary to the LLM story. |
| Full Stack Engineer | HIGH | Integrated | Strong differentiation bullet for Full Stack — cloud API + accessibility + 4-language scope. |
| Defense/Aerospace | LOW | — | Omit. |

---

### RC-04: PDF Parsing for Medical Reports
**Significance:** Document processing pipeline with a domain-aware parsing strategy — shows ability to handle real-world unstructured data.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Implemented | Use as context for how the LLM receives its input. "Document intelligence" framing. |
| Full Stack Engineer | MED | Implemented | Supporting bullet for RC-01 data pipeline story. |
| Defense/Aerospace | LOW | — | Omit. |

---

### RC-05: Two-Call Gemini Architecture
**Significance:** Deliberate API architecture decision — running two sequential LLM calls within one response cycle, delivering two distinct outputs atomically.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | HIGH | Architected | Use alongside RC-02 as the "how I designed the LLM layer" detail. Shows inference pipeline design thinking. |
| Full Stack Engineer | MED | Architected | Use as API design bullet. "Minimizing round trips" is a backend engineering signal. |
| Defense/Aerospace | LOW | — | Omit. |

---

---

## SIGNALML (Raytheon/RTX Capstone)

### SM-01: Two-Layer Stateful LSTM for QPSK Baud-Lock
**Significance:** Strongest quantified ML result in the entire portfolio — applied recurrent ML to a real signal-processing problem with measurable outcomes, under professional engineering guidance.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | HIGH | Built | Lead bullet for SignalML. Emphasize LSTM architecture, streaming inference, and quantified metrics (95.5% baud-mask accuracy, 0.0019 on-baud MSE). Frame as applied ML on real signals data. |
| Full Stack Engineer | LOW | — | Omit. No frontend/web engineering component. |
| Defense/Aerospace | HIGH | Built | Lead bullet for SignalML. Emphasize Raytheon/RTX sponsorship, QPSK domain, and quantified benchmark results. This is the strongest defense credential in the portfolio. |

**Overclaiming warning:** Do NOT claim the full Raytheon system. Nick owned the ML modeling layer only. ~44 samples/sec is notebook visualization, not production throughput.
**First-pass checklist:** [x] "Raytheon/RTX-sponsored capstone" framing [x] Metrics from notebook benchmark [x] "baud-lock" and "QPSK" are correct domain terms

---

### SM-02: is_on_baud Timing Head Design
**Significance:** The core innovation — reframing baud-lock as a sequence prediction problem rather than a rule-based correction, and the primary contribution to the RTX patent disclosure.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | HIGH | Designed | Frame as model architecture innovation — "jointly-learned sequence output" vs. rule-based correction. Show design thinking. |
| Full Stack Engineer | LOW | — | Omit. |
| Defense/Aerospace | HIGH | Designed | Frame as the key technical contribution to the patent disclosure. Use alongside SM-07 for maximum impact. |

---

### SM-03: Hyperparameter Tuning with Keras Tuner
**Significance:** Systematic ML experimentation across architecture space — demonstrates rigorous methodology, not one-shot model building.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Applied | Supporting bullet for SM-01. Shows methodology rigor. |
| Full Stack Engineer | LOW | — | Omit. |
| Defense/Aerospace | MED | Applied | Supporting bullet. Shows structured engineering approach valued in defense environments. |

---

### SM-04: Internal LSTM Activation Inspection
**Significance:** Model interpretability for a high-stakes domain — validates that learned representations correspond to the intended signal behavior.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Conducted | Frame as model interpretability / explainability work. Secondary to SM-01/SM-02. |
| Full Stack Engineer | LOW | — | Omit. |
| Defense/Aerospace | MED | Conducted | Frame as model validation for a defense-relevant application. Defense employers value verifiable model behavior. |

---

### SM-05: Streaming Prediction Pipeline + Benchmarks
**Significance:** Final deliverable evidence — streaming inference with documented performance metrics, produced for a professional engineering audience.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Implemented | Use as supporting benchmark detail alongside SM-01. |
| Full Stack Engineer | LOW | — | Omit. |
| Defense/Aerospace | HIGH | Implemented | Frame as capstone deliverable — streaming inference pipeline with documented performance artifacts. The benchmark metrics are the proof of delivery. |

**Benchmark caveat:** NEVER describe ~44 samples/sec as production throughput. "Notebook UI benchmark" or "visualization benchmark."

---

### SM-06: Label Alignment and Resampling Logic
**Significance:** Signal-aware data preprocessing — shows ability to work with time-series I/Q data and understand timing structure in simulated signals.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Developed | Supporting data pipeline detail. Signals experience in ML context. |
| Full Stack Engineer | LOW | — | Omit. |
| Defense/Aerospace | MED | Developed | Shows signals domain familiarity — I/Q data, timing offsets, raised-cosine simulation. |

---

### SM-07: Patent Disclosure Contribution
**Significance:** Only patent-adjacent credential in the portfolio — differentiates Nick from most new-grad applicants for defense and research-adjacent roles.

| Role Type | Emphasis | Lead Verb | Framing Angle |
|-----------|----------|-----------|---------------|
| ML/AI Engineer | MED | Contributed | Supporting credential. Frame as applied ML research contribution. |
| Full Stack Engineer | LOW | — | Omit. |
| Defense/Aerospace | HIGH | Contributed | Strong differentiator. Use as standalone bullet or combine with SM-02. Always use "RTX patent disclosure process" framing. |

**Overclaiming warning:** NEVER say "filed a patent," "awarded a patent," or "my patent." Patent process is Raytheon/RTX's. Correct: "contributed to an RTX patent disclosure process."

---

## Priority Summary by Role Type

### ML/AI Engineer — HIGH Priority Achievements
SM-01, SM-02, CT-01, CT-02, EP-01, EP-02, EN-01, RC-02, RC-05

### ML/AI Engineer — MED Priority Achievements
SM-03, SM-04, SM-05, SM-06, SM-07, CT-05, EP-03, EN-04, NU-02, RC-01, RC-04

### Full Stack Engineer — HIGH Priority Achievements
CT-03, CT-04, EP-01, EP-02, EP-04, EN-01, EN-02, NU-01, NU-02, NU-03, NU-04, RC-01, RC-03

### Full Stack Engineer — MED Priority Achievements
CT-01, CT-02, CT-05, EP-03, EN-03, EN-04, RC-02, RC-04, RC-05

### Defense/Aerospace — HIGH Priority Achievements
SM-01, SM-02, SM-05, SM-07, EN-02

### Defense/Aerospace — MED Priority Achievements
SM-03, SM-04, SM-06, EP-01, EP-02, EN-01, RC-02, CT-01
