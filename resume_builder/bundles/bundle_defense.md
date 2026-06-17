---
name: bundle_defense
description: Defense/Aerospace bundle — Tier 2; leads heavily on SignalML (Raytheon capstone + patent); supplemented by EcoNauts (Docker) and EcoPrompt (local inference)
metadata:
  type: bundle
---

# Bundle: Defense / Aerospace

> Target employers: Raytheon, L3Harris, Northrop Grumman, Leidos, SAIC, Aerospace Corp
> Tier: 2 — strong with targeted emphasis (anchored by Raytheon capstone)

---

## S1: Role Profile & Priority Matrix

**Positioning:** Nick's Raytheon/RTX-sponsored capstone is a rare and direct credential for a new-grad defense applicant — he has already worked within RTX engineering constraints, contributed to a patent disclosure process, and delivered quantified ML benchmarks for a real signals problem (QPSK baud-lock via LSTM). Supplement with the EcoNauts 1st-place award (team delivery + Docker) and EcoPrompt's local inference angle (Ollama = no cloud dependency, which maps to air-gapped/on-prem deployment contexts in defense). Frame as: "new grad with prior RTX exposure, ML depth in signal processing, and demonstrated delivery under professional constraints."

**Important:** Position Nick's Raytheon capstone prominently in the resume header or experience section — it is the strongest differentiator for any defense application. If the target employer is Raytheon/RTX specifically, this is an explicit prior relationship.

### Priority Matrix
| Priority | Achievement IDs | Rationale |
|----------|----------------|-----------|
| HIGH | SM-01, SM-02, SM-05, SM-07, EN-02 | QPSK ML modeling (quantified), timing head innovation, streaming deliverable, patent disclosure, Docker/containerization |
| MED | SM-03, SM-04, SM-06, EP-01, EP-02, EN-01, RC-02, CT-01 | Methodology rigor, signal preprocessing, local inference (air-gapped angle), ML model serving, applied AI |
| LOW | CT-02, CT-03, CT-04, CT-05, EP-03, EP-04, EN-03, EN-04, NU-01–04, RC-01, RC-03, RC-04, RC-05 | Web/mobile/health-tech work — omit |

### Recommended Project Selection (1-page resume, 3 projects)
1. **SignalML** (lead — anchor) — SM-01 + SM-02 + SM-07
2. **EcoNauts** — EN-01 + EN-02 (API + Docker)
3. **EcoPrompt** — EP-01 + EP-02 (RAG backend + local inference / no cloud dependency)
- redClarity RC-02 as optional 4th if JD mentions AI/NLP

---

## S2: Summary Guide

**Headline pattern:** `CS new grad with Raytheon/RTX-sponsored capstone experience — recurrent ML for signal timing recovery, QPSK I/Q data, and RTX patent disclosure contribution.`

**Building blocks** (phrases to draw from for the summary):
- "Raytheon/RTX-sponsored senior capstone"
- "recurrent ML for QPSK symbol timing recovery and baud-lock"
- "contributed to RTX patent disclosure process"
- "95.5% baud-mask accuracy, 0.0019 on-baud MSE in streaming benchmarks"
- "Python, TensorFlow/Keras, LSTM, NumPy, SciPy signal processing"
- "Docker Compose for multi-service containerization"
- "local LLM inference (Ollama) — no cloud API dependency"

**Avoid:**
- Claiming the full Raytheon system or CNN/baseline direction
- "filed a patent" or "awarded a patent" — always "contributed to RTX patent disclosure"
- ~44 samples/sec as production inference speed (notebook benchmark only)
- Overstating clearance eligibility — do not claim clearance unless you have it
- Any mention of proprietary system integration details or customer context

---

## S3: Achievement Reframing Map

| ID | Default Framing | Defense/Aerospace Framing | Key Metric / Signal |
|----|----------------|--------------------------|---------------------|
| SM-01 | LSTM for QPSK baud-lock | Applied ML in a Raytheon/RTX-sponsored context — recurrent model for real signals problem; quantified benchmark results | 95.5% baud-mask accuracy, 0.0019 on-baud MSE, Raytheon capstone |
| SM-02 | is_on_baud timing head | Technical innovation — reframed baud-lock as a learnable sequence prediction problem; core contribution to patent disclosure | Patent disclosure contribution |
| SM-05 | Streaming benchmarks | Professional deliverable evidence — streaming inference pipeline with documented performance metrics for RTX engineering review | 0.08497 val loss, 95.5% accuracy |
| SM-07 | Patent disclosure | Strongest new-grad credential for defense employers — technical contribution to an RTX-handled patent disclosure for ML signal timing recovery | RTX patent disclosure |
| EN-02 | Docker Compose | Multi-service container orchestration — cross-container networking, reliable startup sequencing for a 4-service stack | Sole authorship |
| EN-01 | FastAPI routing (ML → frontend) | Systems integration — API layer connecting ML model outputs to frontend; demonstrates ability to work in multi-component systems | 1st place FullyHacks 2025 |
| EP-01 | RAG backend | Local AI inference — RAG pipeline using locally-run Ollama LLM, no cloud API dependency (maps to air-gapped/on-prem deployment) | 30% token reduction, local inference |
| EP-02 | FastAPI→Ollama | On-prem LLM deployment pattern — deliberate local inference to eliminate external dependency | Zero cloud dependency |

---

## S4: Skills Guide

**Bold tools (resume Technical Skills section):**
Python, TensorFlow, Docker, NumPy, Git

**Must-include skills (ATS match for Defense/Aerospace roles):**
Python, TensorFlow, NumPy, scikit-learn, Docker, Git, Google Cloud Platform

**Nice-to-have (include if budget allows):**
FastAPI, Flask, PostgreSQL, C++ (if JD mentions embedded or systems programming)

**Omit or deprioritize for defense audience:**
React, Next.js, SvelteKit, Node.js, Gemini API (unless JD mentions commercial AI integration), SwiftUI/Swift

**Notes:**
- TensorFlow is strongly evidenced by SignalML (Keras/LSTM) — safe to lead
- NumPy and SciPy: evidenced by SignalML signal processing work — safe to include
- scikit-learn: config-declared only for Nick; EcoNauts RF was teammates'; list but do not lead
- C++: config-declared only; include if JD asks for embedded or low-level systems work
- Do not list TensorBoard as a standalone skill — it's a tool, not a skill for the skills table

**Security clearance:** Do not make any clearance claims. Nick does not currently hold a clearance. Mention eligibility (US citizen) only if the employer's posting requires it and you have confirmed this fact.

---

## S5: Cover Letter Guide

**Institution type:** Defense prime contractors (Raytheon, Northrop, L3Harris, Leidos, SAIC) and research labs (Aerospace Corp, MITRE, JHU APL)

**Opening hook patterns:**
- *Raytheon/RTX specifically:* "I contributed the recurrent ML modeling and evaluation work for a Raytheon/RTX-sponsored capstone at CSUF — designing a stateful LSTM for QPSK baud-lock, achieving 95.5% baud-mask accuracy in streaming benchmarks, and contributing to an RTX patent disclosure process. I'm applying to [role] to continue that work in a professional engineering context."
- *Other defense prime:* "As part of a Raytheon/RTX-sponsored senior capstone, I designed and benchmarked a two-layer stateful LSTM for QPSK symbol timing recovery — contributing the recurrent-model prototype and is_on_baud timing head to an RTX patent disclosure process. That experience gave me hands-on exposure to professional engineering constraints in a signals context that I want to build on."
- *Research lab (Aerospace Corp, MITRE):* "My interest in [lab] comes from the intersection of ML and signals that defined my senior capstone — a Raytheon/RTX-sponsored project applying recurrent ML to QPSK baud-lock, where I contributed to a patent disclosure process and produced streaming benchmarks for an RTX engineering audience."

**Key narrative thread:** "RTX-connected new grad with ML depth in signals" — the Raytheon capstone is the anchor, and every other project is supporting evidence of delivery capability (EcoNauts: award-winning team delivery; EcoPrompt: solo backend ownership; Docker/containerization). The thread is: prior professional exposure to defense engineering constraints + ML engineering skills + demonstrated delivery on a team.

**"Why them" angle (what to research):**
- Whether the role overlaps with signals, communications, or sensing — direct SignalML bridge
- Whether the role mentions ML/AI in a defense context — SignalML + patent disclosure
- Whether the role mentions containerization or DevOps — EN-02 is the hook
- Whether they have an existing RTX/Raytheon relationship (if applying to RTX divisions: mention capstone explicitly)
- Whether the role mentions Python, TensorFlow, signal processing — direct stack match

**Avoid:**
- Mentioning any proprietary Raytheon system context, customer requirements, or CNN/baseline direction
- Claiming patent ownership — "contributed to RTX patent disclosure process" only
- Implying a security clearance you don't have
- Leading with non-defense projects (Chess Tutor, Nuri, redClarity) in defense CLs — bury or omit
- Overstating the capstone scope — Nick owned the ML modeling layer; RTX engineers owned the system context
