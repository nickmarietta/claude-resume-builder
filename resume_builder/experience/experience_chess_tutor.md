---
name: experience_chess_tutor
description: Chess Tutor Web App — solo project, beta with real users; PGN→Stockfish→LLM coaching pipeline
metadata:
  type: experience
---

# Experience: Chess Tutor Web App
## 2025 — Solo Personal Project (active)

### Cross-Project Section
Chess Tutor is Nick's most complete demonstration of solo AI product ownership: the only project where he designed, built, and shipped every layer — from Stockfish WASM integration to LLM prompt engineering to beta user iteration. It shows product instinct (real users, v1 release, feedback-driven improvement) alongside the ability to bridge search-based and generative AI in a single user-facing system.

**CL framing:** Use Chess Tutor to demonstrate end-to-end ownership, agentic AI design thinking, and the ability to take an AI product from concept to real-user deployment without a team.

---

### Achievement CT-01: End-to-End AI Coaching Pipeline
**Source:** marietta2025_chess_tutor.md
**Paper:** N/A — personal project
**User's role:** Sole developer and product owner
**Status:** Beta — live with real users

**Context:** Chess improvement tools typically require users to manually interpret engine output. Chess Tutor eliminates that gap by chaining Stockfish evaluation directly into an LLM explanation layer, delivering natural-language coaching automatically.

**Bullet variants:**
- **2L:** Built an end-to-end AI chess coaching pipeline — PGN import → Stockfish evaluation → LLM natural-language output — serving real beta users with move-by-move feedback for every game submitted.
- **3L:** Architected and sole-developed an end-to-end AI chess coaching pipeline integrating PGN game import, Stockfish evaluation, and LLM natural-language explanation, delivering move-by-move coaching feedback to real beta users with no human-in-the-loop intervention at any stage of the process.
- **1L:** Built PGN→Stockfish→LLM coaching pipeline serving real beta users with move-by-move AI feedback.

**Key skills:** LLM integration, prompt engineering, Stockfish, PGN parsing, end-to-end system design, TypeScript
**ATS keywords:** LLM pipeline, generative AI, agentic AI, prompt engineering, AI product, real users
**Reframing notes:** ML/AI — emphasize agentic design and search+generative AI bridge. Full Stack — emphasize pipeline architecture and user-facing product delivery. Defense — de-emphasize; use only if JD mentions AI integration.

---

### Achievement CT-02: Prompt Engineering for Engine-to-Language Translation
**Source:** marietta2025_chess_tutor.md
**Paper:** N/A — personal project
**User's role:** Sole developer
**Status:** Beta — live with real users

**Context:** Raw Stockfish output is numerical (centipawn scores, move sequences) and meaningless to most users. Translating it into plain-English coaching requires carefully engineered prompts that interpret evaluation context without hallucinating moves or misstating positions.

**Bullet variants:**
- **2L:** Engineered system prompts translating raw Stockfish output (centipawn scores, best-move sequences) into plain-English coaching feedback, bridging search-based and generative AI within a single user-facing product.
- **3L:** Designed and iterated on system-level prompts to translate raw Stockfish evaluation data — centipawn loss values and best-move sequences — into plain-English coaching explanations, bridging search-based AI (Stockfish) with generative AI (LLM) in a unified, agentic product pipeline serving real users.
- **1L:** Engineered LLM prompts translating Stockfish centipawn scores and move sequences into plain-English coaching feedback.

**Key skills:** Prompt engineering, LLM, system prompts, Stockfish, generative AI
**ATS keywords:** prompt engineering, LLM, generative AI, system prompts, AI coaching
**Reframing notes:** ML/AI — lead with "bridging search-based and generative AI" framing. Full Stack — emphasize user-facing output quality. Defense — low relevance unless JD mentions NLP/AI.

---

### Achievement CT-03: Interactive Board UI + Session History Model
**Source:** marietta2025_chess_tutor.md
**Paper:** N/A — personal project
**User's role:** Sole developer
**Status:** Beta — live with real users

**Context:** A coaching tool without game history is stateless — users can't track their improvement. The session history model was designed to let users see patterns in their mistakes over time, requiring persistent state management and a game-record schema.

**Bullet variants:**
- **2L:** Designed and implemented an interactive chess board with move-by-move navigation and a session history model to surface user habit patterns over time, supporting ongoing user-driven feature iteration.
- **3L:** Designed and implemented an interactive chess board interface with full move-by-move navigation and game replay controls, paired with a session history model that persists game records across visits to surface recurring mistake patterns and habit data for individual users over time.
- **1L:** Built interactive chess board UI with move-by-move navigation and a session history model for habit tracking.

**Key skills:** TypeScript, UI design, state management, game history modeling, frontend engineering
**ATS keywords:** frontend, state management, UI, user experience, TypeScript
**Reframing notes:** Full Stack — strong fit, lead with UI + data modeling. ML/AI — secondary; mention if space allows. Defense — omit.

---

### Achievement CT-04: Stockfish WASM Integration
**Source:** marietta2025_chess_tutor.md
**Paper:** N/A — personal project
**User's role:** Sole developer
**Status:** Beta — live with real users

**Context:** Running Stockfish in-browser via WebAssembly introduces async evaluation constraints that don't exist in a server-side context. Resolving these required understanding the WASM execution model and designing an async-safe pipeline from eval request to LLM input.

**Bullet variants:**
- **2L:** Integrated Stockfish via WebAssembly in a browser environment, resolving async evaluation constraints to deliver real-time chess engine analysis client-side without a dedicated evaluation server.
- **3L:** Integrated the Stockfish chess engine via WebAssembly for client-side deployment, diagnosing and resolving asynchronous evaluation constraints inherent to WASM execution in the browser to deliver real-time engine analysis without requiring a dedicated server-side evaluation process.
- **1L:** Integrated Stockfish via WASM, resolving async constraints to enable real-time engine analysis in-browser.

**Key skills:** WebAssembly (WASM), Stockfish, async programming, TypeScript, browser-side AI
**ATS keywords:** WebAssembly, WASM, Stockfish, async, chess engine, browser integration
**Reframing notes:** Full Stack — strong fit (browser engineering challenge). ML/AI — secondary. Defense — omit.

---

### Achievement CT-05: v1 Release and User Feedback Iteration
**Source:** marietta2025_chess_tutor.md
**Paper:** N/A — personal project
**User's role:** Sole developer and product owner
**Status:** Beta — live with real users

**Context:** Shipping to real users and iterating based on feedback demonstrates product judgment that purely technical projects lack. This achievement shows the full loop: build → release → observe → improve.

**Bullet variants:**
- **2L:** Shipped v1 release and iterated on LLM explanation quality based on direct beta user feedback, demonstrating end-to-end product ownership from initial deployment through data-informed improvement cycles.
- **3L:** Planned, shipped, and managed the v1 release of Chess Tutor, then actively iterated on LLM explanation quality by collecting and acting on direct beta user feedback — demonstrating full product lifecycle ownership from initial release through user-driven improvement across subsequent versions.
- **1L:** Shipped v1 release and iterated on LLM explanation quality based on feedback from real beta users.

**Key skills:** Product ownership, release management, user feedback, iterative development
**ATS keywords:** product ownership, iterative development, user feedback, release management
**Reframing notes:** ML/AI — emphasize AI product iteration and user-driven improvement. Full Stack — emphasize shipping and deployment. Defense — omit unless JD mentions rapid prototyping.

---

### Provenance Guardrails (All CT Achievements)
- NEVER say "deployed" or "in production" — correct framing is "beta with real users"
- Sole contributor on all claims — no hedging needed, but do not overstate user scale
- Do not cite specific user counts (not documented)
