---
name: marietta2025_ecoprompt
description: EcoPrompt hackathon project — Nick built the full backend (RAG system, FastAPI→Ollama, HumanDelta, PostgreSQL); 30% token reduction measured via HumanDelta; team of 3, no award
metadata:
  type: project
---

# EcoPrompt — AI Prompt Optimizer for Reduced Compute

## Metadata
- **Project owner:** **Nicklaus Marietta** (backend) + 2 teammates (frontend)
- **Year:** 2026 (FullyHacks 2026, CSUF hackathon)
- **Type:** Team hackathon project (3 people)
- **Status:** Hackathon submission — no award
- **Correct framing:** "resulted in 30% reduction in token usage" — never claim award (per config.md)

## Methods & Tools
- **Backend framework:** FastAPI (Python)
- **Local LLM runtime:** Ollama (`qwen2.5:1.5b`) — local inference, no cloud API
- **RAG system:** Retrieval-Augmented Generation pipeline (Nick built and completed)
- **Evaluation framework:** HumanDelta (prompt scoring; source of the 30% metric)
- **Database:** PostgreSQL via Neon (persistent prompt storage and comparison history)
- **Frontend (teammates):** Next.js, React, Tailwind CSS
- **Pipeline:** User prompt → RAG-augmented Ollama rewrite → HumanDelta scoring → environmental impact visualization

## Key Results
1. 30% reduction in token usage measured by HumanDelta, comparing prompts before and after rewriting
2. Completed and integrated a full RAG system powering the prompt rewriting pipeline
3. Wired FastAPI → Ollama connection enabling local LLM inference with no cloud API dependency during demo
4. Integrated HumanDelta evaluation framework to produce real-time environmental impact scoring
5. Set up PostgreSQL (Neon) schema for storing prompt history and before/after comparison data
6. Delivered working end-to-end demo at FullyHacks 2026 across a 3-service architecture (Ollama, FastAPI, Next.js)

## Novelty Claims
- RAG-powered prompt rewriting for efficiency/sustainability — not just prompt summarization
- Local inference (Ollama) used deliberately to avoid cloud API costs and latency during demo
- HumanDelta integration as an environmental impact metric layer — connects AI efficiency to sustainability framing

## Collaboration & Scope
- **Team size:** 3 people
- **Nick's ownership:** Full backend — RAG system, FastAPI, Ollama integration, HumanDelta integration, PostgreSQL schema
- **Teammates' ownership:** Next.js frontend (React, Tailwind CSS)
- **Shared:** Overall product concept and demo delivery

## Provenance Notes
- **Publication status:** N/A — hackathon project
- **Safe to claim:** All backend contributions; RAG system; FastAPI→Ollama wiring; HumanDelta integration; PostgreSQL setup; 30% token reduction metric (HumanDelta output)
- **Needs hedging:** Frontend work — do not claim; teammates built it. Use "contributed to" for full-product framing.
- **Do NOT claim:** Award or placement (no award). Do not say "deployed." Do not claim frontend ownership.

## Resume Bullet Seeds
1. Built a RAG-powered prompt rewriting backend in FastAPI, integrating a local Ollama LLM to optimize user prompts and reduce token usage by 30% as measured by HumanDelta
2. Designed and wired the FastAPI → Ollama inference pipeline using a locally-run `qwen2.5:1.5b` model, eliminating cloud API dependency and latency for live demo conditions
3. Integrated the HumanDelta evaluation framework to score prompt efficiency and render real-time environmental impact metrics alongside rewritten prompts
4. Set up PostgreSQL (Neon) schema for persistent prompt history and before/after comparison storage across the three-service backend
5. Contributed backend and LLM infrastructure for an AI sustainability tool demoed at FullyHacks 2026 with a 3-person team
