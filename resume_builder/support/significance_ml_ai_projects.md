---
name: significance_ml_ai_projects
description: Field context for ML/AI Engineer cover letters — why Nick's AI projects matter, competing approaches, industry context
metadata:
  type: support
---

# Significance Research: ML / AI Engineer Projects

> Use in cover letters and summaries — NOT in resume bullet text.
> These provide field context that demonstrates Nick understands the AI landscape.

---

### SM-01/SM-02: Field Context — ML-Based Symbol Timing Recovery
**The problem:** Symbol timing recovery (baud-lock) is a foundational step in digital communications receivers. Without accurate timing, a receiver can't reliably decode transmitted symbols — even small drift or slip accumulates into decoding failures. Traditional approaches use rule-based timing error detectors (e.g., Mueller-Müller, Gardner) that require explicit signal models and tune poorly to non-standard or adversarial channels.

**Competing approaches:** Rule-based timing error detectors (TEDs) are the standard; they're analytically tractable but require explicit knowledge of the modulation scheme and pulse shape. CNN-based approaches have been explored for symbol classification but typically require post-hoc timing correction. Nick's contribution — an LSTM with a jointly-trained is_on_baud head — frames timing recovery as a sequence prediction problem, allowing the model to learn drift and slip patterns from data rather than requiring an explicit model.

**Why this matters:** As ML-based signal processing (sometimes called "AI-native radio" or "cognitive communications") gains traction in defense and communications R&D, replacing hand-engineered signal processing blocks with learned alternatives is a priority area. Raytheon/RTX's sponsorship signals that this direction is considered worth patenting.

**Differentiation:** Nick's approach is distinct in framing baud-lock as a learnable sequence output (is_on_baud) rather than a post-hoc correction step — this means the model is simultaneously recovering I/Q values and predicting timing validity, enabling joint optimization.

---

### EP-01: Field Context — RAG for Prompt Efficiency
**The problem:** As LLM usage scales, token consumption becomes a significant cost and environmental factor. Users write inefficient prompts — verbose, redundant, or structurally suboptimal — that inflate token counts without improving output quality.

**Competing approaches:** Prompt compression tools (LLMLingua, etc.) typically summarize or truncate inputs. Prompt optimization via human review is manual and doesn't scale. EcoPrompt's RAG-based approach is different: it rewrites prompts using a local LLM augmented by retrieval, targeting efficiency without summarization-style information loss.

**Why this matters:** Green AI / sustainable computing is an active concern at major AI labs and policy bodies (MLCommons, DOE). Tools that reduce compute without sacrificing quality have commercial and regulatory tailwinds. The HumanDelta evaluation framework provides a standardized measurement layer that makes the 30% figure reproducible and externally verifiable.

**Differentiation:** Local inference (Ollama) eliminates cloud API dependency — relevant for latency-sensitive or privacy-constrained environments. The RAG layer adds domain-relevant retrieval context to the rewrite process, distinguishing it from pure summarization.

---

### CT-01/CT-02: Field Context — LLM-Powered Chess Coaching
**The problem:** Chess improvement tools (Stockfish, Lichess analysis) produce engine evaluations that are numerical and opaque to improving players. Centipawn scores and "best move" sequences require domain expertise to interpret — most players don't know what a -150cp blunder means in plain language.

**Competing approaches:** Lichess and Chess.com provide text explanations for some positions, but these are canned or crowd-sourced, not dynamically generated per position. AI coaching tools like ChessGPT exist but typically don't integrate live engine evaluation. Chess Tutor's approach — bridging Stockfish evaluation with an LLM explanation layer — creates a genuinely agentic coaching loop.

**Why this matters:** AI tutoring and personalized feedback is a growing application area across games, education, and professional training. The design pattern (search engine → LLM → natural language output) generalizes to any domain where expert tools produce structured output that users can't interpret without assistance.

**Differentiation:** Chess Tutor is the only project in Nick's portfolio where he shipped v1 to real users and iterated based on feedback — demonstrating product instinct alongside technical execution.

---

### RC-02: Field Context — Medical Document AI
**The problem:** Patients who receive Comprehensive Metabolic Panel (CMP) lab results often receive raw numerical values with reference ranges but no plain-English interpretation. Non-English-speaking patients face an additional barrier. The result is that actionable health information remains inaccessible to the people who most need it.

**Competing approaches:** Patient portal explanations (Epic, MyChart) provide generic reference-range flags but don't generate personalized interpretations or follow-up questions. LLM tools like ChatGPT can be prompted ad-hoc, but require patients to know how to query effectively and don't structure follow-up questions for physician visits.

**Why this matters:** Health literacy and patient empowerment are priorities across the healthcare system. Tools that make clinical data accessible to non-clinical users reduce downstream care costs and improve patient outcomes. The multilingual output (English, Spanish, French, Vietnamese) demonstrates accessibility design thinking, not just technical capability.

**Differentiation:** The two-prompt architecture (explanation + physician questions in one response) is designed for a specific user workflow — a patient who will take both outputs to their next doctor's appointment. This is domain-aware design, not a generic "summarize this" prompt.

---

## Field Overview: Applied LLM Engineering (2025–2026)

The LLM application layer has matured rapidly in 2025–2026. The distinguishing factor between "toy demo" and "engineering" projects is no longer which API you call — it's whether you made deliberate architectural decisions about how to use it. Nick's projects reflect this: Chess Tutor makes an agentic no-HITL decision; redClarity makes a two-call sequential architecture decision; EcoPrompt makes a local inference decision. Each choice reflects an understanding of LLM deployment tradeoffs, not just API integration.

For ML/AI Engineer roles at AI labs and product companies, the relevant signal is: can this person build an AI-powered feature end-to-end, make sensible architecture decisions, and produce something a real user can use? Chess Tutor (beta users), redClarity (health-tech application), and EcoPrompt (measured efficiency outcome) collectively answer yes.

The RAG pattern specifically is in high demand — retrieval-augmented generation has become the dominant approach for grounding LLM outputs in domain-specific knowledge. EcoPrompt's implementation of a full RAG pipeline is strong evidence that Nick can build this class of system from scratch, not just call a wrapper library.

---

## Field Overview: ML for Signal Processing (Emerging)

ML-based signal processing — replacing hand-engineered signal processing blocks with learned alternatives — is a growing research and product area, particularly in defense, communications, and RF/radar domains. Traditional digital signal processing (DSP) requires expert knowledge of the modulation scheme, channel model, and signal parameters; learned approaches can generalize across channel conditions and adapt to non-standard signals.

The QPSK baud-lock problem is a representative example of a signal processing task where ML approaches have potential advantages over rule-based methods: the learned model can absorb timing-error correction into its sequence prediction task, rather than requiring a separate timing error detector and loop filter. This is the design insight behind Nick's is_on_baud timing head.

For defense employers, the combination of Raytheon/RTX sponsorship + patent disclosure contribution + quantified benchmark results is a strong new-grad credential in this space. It signals domain exposure, professional engineering context, and the ability to contribute to patentable technical work — all uncommon at the new-grad level.
