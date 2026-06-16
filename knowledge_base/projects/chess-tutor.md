# Project: Chess Tutor Web App

## Overview
A web application that allows users to import PGN chess games and receive move-by-move feedback powered by the Stockfish chess engine. The LLM layer translates engine evaluations into natural language explanations, making engine analysis accessible to non-expert players. Currently in active development with real beta users.

## Status
`beta` — deployed with real users, ongoing development (v1 publicly tagged)

## Role
Solo developer and product owner. Responsible for full system design, frontend, Stockfish integration, LLM prompt engineering, and user feedback loop.

## Tech Stack
- **Frontend:** HTML, TypeScript (HTML 72.8%, TypeScript 26.9% per repo)
- **Chess Engine:** Stockfish (WASM or server-side integration for move evaluation)
- **LLM Layer:** Large language model for natural language move explanation
- **PGN Parsing:** Game import and move replay logic
- **Tooling:** Graphify for codebase visualization

## What I Built / My Contributions
- Designed and implemented the full pipeline: PGN import → board rendering → Stockfish evaluation → LLM explanation output
- Engineered prompts to translate raw Stockfish centipawn scores and best-move suggestions into plain English coaching feedback
- Built the interactive board UI with move-by-move navigation
- Architected the system to track user habits over time (ongoing feature)
- Managed version 1 release and iterated based on real user feedback

## Key Technical Challenges
- Bridging the gap between raw engine output (centipawn loss, best move sequences) and human-readable coaching language required careful prompt engineering
- Integrating Stockfish in a web environment (WASM constraints, async evaluation)
- Designing a session/game history model to enable habit tracking across visits

## Outcomes / Metrics
- Live with real beta users receiving feedback
- Version 1 shipped; actively iterating on LLM explanation quality
- Identified as an agentic AI system: takes game input, reasons via engine, produces natural language output with no human in the loop

## Significance for Resume
- Demonstrates end-to-end AI system design (not just model usage — full pipeline ownership)
- Shows product instincts: built for real users, not just as a demo
- Relevant to: ML Engineer, Full Stack Engineer, AI/LLM Engineer roles
- Talking point: "built a system that bridges search-based AI (Stockfish) with generative AI (LLM) in a single user-facing product"

## Tags
`ai`, `llm`, `full-stack`, `chess`, `web-app`, `typescript`, `html`, `stockfish`, `prompt-engineering`, `solo`, `beta`, `user-facing`
