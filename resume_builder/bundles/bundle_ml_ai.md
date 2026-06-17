---
name: bundle_ml_ai
description: ML/AI Engineer bundle — Tier 1, strongest evidence; leads with SignalML + EcoPrompt + Chess Tutor + redClarity
metadata:
  type: bundle
---

# Bundle: ML / AI Engineer

> Target employers: AI labs, tech companies, defense R&D
> Tier: 1 — strongest evidence, full portfolio

---

## S1: Role Profile & Priority Matrix

**Positioning:** Nick is a new-grad CS engineer with hands-on experience building LLM-powered products (Chess Tutor, redClarity), a RAG system with a measured outcome (EcoPrompt, 30% token reduction), and recurrent ML for a real signals application (SignalML, Raytheon/RTX capstone). His signal is breadth-with-depth: he's shipped AI to real users, contributed to a patent disclosure, and built in multiple LLM APIs and ML frameworks. Frame as "applied AI engineer who builds things that work" — not a theorist.

### Priority Matrix
| Priority | Achievement IDs | Rationale |
|----------|----------------|-----------|
| HIGH | SM-01, SM-02, SM-07, CT-01, CT-02, EP-01, EP-02, EN-01, RC-02, RC-05 | Quantified ML results, LLM product delivery, RAG, patent contribution, model serving |
| MED | SM-03, SM-04, SM-05, SM-06, CT-05, EP-03, EN-04, NU-02, RC-01, RC-04 | Supporting methodology, streaming benchmarks, product iteration, secondary AI claims |
| LOW | CT-03, CT-04, EP-04, EP-05, EN-02, EN-03, NU-01, NU-03, NU-04, RC-03 | UI/frontend work, database, Docker, mobile — omit unless JD specifically calls for it |

### Recommended Project Selection (1-page resume, 4 projects)
1. **SignalML** (lead) — SM-01 + SM-02 or SM-07
2. **EcoPrompt** — EP-01 (RAG + 30% metric)
3. **Chess Tutor** — CT-01 + CT-02 (pipeline + prompts)
4. **redClarity** — RC-02 + RC-05 (Gemini prompts + architecture)
- EcoNauts (EN-01) as 5th project if resume has a third bullet slot in one section

---

## S2: Summary Guide

**Headline pattern:** `CS new grad building AI-powered applications — LLM pipelines, RAG systems, and recurrent ML for signal processing.`

**Building blocks** (phrases to draw from for the summary):
- "end-to-end LLM-powered applications"
- "RAG pipeline with measurable efficiency outcomes"
- "recurrent ML for signal timing recovery (Raytheon/RTX capstone)"
- "prompt engineering across medical and games domains"
- "agentic AI design — no human-in-the-loop"
- "contributed to RTX patent disclosure process"

**Avoid:**
- "senior" or "lead" framing
- Claiming ML model ownership for EcoNauts (teammates' models)
- "deployed" or "production" for Chess Tutor
- Any mention of the Raytheon system beyond Nick's ML modeling layer

---

## S3: Achievement Reframing Map

| ID | Default Framing | ML/AI Engineer Framing | Key Metric |
|----|----------------|----------------------|------------|
| SM-01 | LSTM for QPSK baud-lock | Applied ML for real-world signal timing recovery — Raytheon/RTX capstone; recurrent model with quantified benchmark | 95.5% baud-mask accuracy, 0.0019 on-baud MSE |
| SM-02 | is_on_baud timing head | Novel model architecture: framing baud-lock as jointly-learned sequence prediction vs. rule-based correction | Core patent disclosure contribution |
| SM-07 | Patent disclosure | Technical contribution to RTX patent disclosure for ML-based timing recovery | Patent-adjacent credential |
| CT-01 | Coaching pipeline | Agentic AI product: no-HITL, search-based + generative AI bridge in a single user-facing system | Real beta users |
| CT-02 | Prompt engineering | Applied prompt engineering with a constrained, structured input domain (chess engine output → NL) | — |
| EP-01 | RAG backend | RAG system with a measured efficiency outcome and local inference architecture | 30% token reduction (HumanDelta) |
| EP-02 | FastAPI→Ollama | Local LLM inference architecture — deliberate choice to avoid cloud dependency | Local, zero-latency for demo |
| EN-01 | FastAPI routing | ML model serving — the integration layer making ML outputs accessible to a frontend | 1st place FullyHacks 2025 |
| RC-02 | Gemini prompt eng. | Medical-domain prompt engineering with real-world accuracy/accessibility tradeoff | 2 system prompts, 4-language output |
| RC-05 | Two-call Gemini | LLM inference pipeline design — sequential calls, atomic response, minimized round trips | — |

---

## S4: Skills Guide

**Bold tools (resume Technical Skills section):**
TensorFlow, Gemini API, FastAPI, Flask, Python

**Must-include skills (ATS match for ML/AI roles):**
Python, TensorFlow, Gemini API, NumPy, scikit-learn, FastAPI, Flask, Git, Docker, Google Cloud Platform

**Nice-to-have (include if budget allows):**
PostgreSQL, TypeScript, React (if JD mentions frontend), AWS

**Omit or deprioritize:**
SvelteKit, Next.js, Node.js (teammate frameworks — no first-party evidence), C++ and Java unless JD specifically calls for them

**Notes:**
- TensorFlow: evidenced by SignalML (LSTM models) — safe to bold; Keras is part of TensorFlow ecosystem
- scikit-learn: config-declared only; EcoNauts RF was teammates' — list but do not lead
- NumPy: evidenced by SignalML (NumPy for signal processing) + config declared

---

## S5: Cover Letter Guide

**Institution type:** AI labs, tech companies (Google DeepMind, Anthropic, OpenAI, startups), defense R&D (Raytheon AI division, MITRE, etc.)

**Opening hook patterns:**
- *LLM-focused companies:* "From building a no-human-in-the-loop chess coaching pipeline to engineering system prompts that translate Stockfish analysis into patient-accessible language, I've spent the past year shipping AI applications that work in production — or close to it."
- *Research/defense:* "As part of a Raytheon/RTX-sponsored capstone, I designed and benchmarked a stateful LSTM for QPSK symbol timing recovery, contributing to an RTX patent disclosure process — work that convinced me that applied ML is where I want to build my career."
- *Startup/general AI:* "I've built a RAG-powered prompt optimization backend (30% token reduction via HumanDelta), a chess coaching LLM pipeline serving real beta users, and a two-call Gemini system for medical document interpretation — three projects where the AI layer wasn't a demo, it was the product."

**Key narrative thread:** "Applied AI engineer with real delivery" — show that Nick builds things that work: a real beta deployment (Chess Tutor), a measured result (EcoPrompt 30%), a professional engineering context (Raytheon capstone), and domain-specific prompt engineering (redClarity medical). The thread is: AI applied to real problems, with engineering discipline.

**"Why them" angle (what to research):**
- What LLM APIs or ML frameworks they use — match to Nick's stack
- Whether they value local inference / edge deployment (Ollama angle)
- Whether they care about evaluation/metrics (HumanDelta angle)
- Any defense/signals adjacency (Raytheon capstone is the bridge)

**Avoid:**
- Claiming to have "built the AI" at Raytheon — frame as ML modeling contribution
- Overstating Chess Tutor user scale
- Saying "I am passionate about AI" without immediately following with a concrete example
- Restating resume bullets verbatim — CL should add the "why I built this" layer
