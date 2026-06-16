---
name: marietta2025_chess_tutor
description: Chess Tutor web app — solo project, beta with real users; PGN-to-LLM coaching pipeline using Stockfish and prompt engineering
metadata:
  type: project
---

# Chess Tutor Web App

## Metadata
- **Project owner:** **Nicklaus Marietta**
- **Year:** 2025 (v1 released; active development)
- **Type:** Solo personal project
- **Status:** Beta — live with real users, ongoing iteration
- **Correct framing:** "beta with real users" — never say "deployed" or "production" (per config.md)

## Methods & Tools
- **Languages:** TypeScript (26.9% of repo), HTML (72.8% of repo)
- **Chess engine:** Stockfish (WASM / server-side integration)
- **LLM layer:** Large language model for natural language move explanation; prompt engineering to translate centipawn scores and best-move sequences into coaching feedback
- **Input format:** PGN (Portable Game Notation) parsing and move replay logic
- **UI:** Interactive board with move-by-move navigation
- **Tooling:** Graphify for codebase visualization
- **Pipeline:** PGN import → board rendering → Stockfish evaluation → LLM explanation output

## Key Results
1. Shipped v1 release; actively iterated based on real beta user feedback
2. Engineered prompts to translate raw Stockfish centipawn loss and best-move sequences into plain English coaching explanations
3. Built full end-to-end pipeline: game import, board rendering, engine evaluation, and natural language output — no human in the loop
4. Architected session/game history model to enable user habit tracking across visits (ongoing feature)
5. Identified as an agentic AI system: takes structured game input, reasons via search-based engine, produces generative natural language output

## Novelty Claims
- Full pipeline bridges search-based AI (Stockfish) with generative AI (LLM) in a single user-facing product
- Agentic design: no human-in-the-loop between game input and coaching output
- Product instinct demonstrated: built for real users, not just as a technical demo

## Collaboration & Scope
- **Other contributors:** None — solo developer and product owner
- **Nick's specific contribution:** All system design, frontend, Stockfish integration, LLM prompt engineering, version management, and user feedback iteration
- **Shared vs. sole work:** Entirely sole-contributor

## Provenance Notes
- **Publication status:** N/A — personal project
- **Safe to claim:** All technical contributions; end-to-end ownership; "beta with real users"; v1 release; prompt engineering for engine-to-language translation
- **Needs hedging:** Nothing — sole contributor
- **Do NOT claim:** "deployed" or "production" status; do not overstate scale of user base (framing is "real beta users," not a large user count)

## Resume Bullet Seeds
1. Built an end-to-end AI coaching pipeline — PGN import → Stockfish evaluation → LLM explanation — serving real beta users with move-by-move natural language feedback
2. Engineered prompts to translate raw chess engine output (centipawn scores, best-move sequences) into plain English coaching feedback, bridging search-based and generative AI in a single product
3. Designed and implemented interactive board UI with move-by-move navigation and session history model to surface user habit patterns over time
4. Integrated Stockfish via WASM in a web environment, resolving async evaluation constraints to deliver real-time engine analysis in the browser
5. Managed v1 release and iterated on LLM explanation quality based on direct beta user feedback
