# Project: EcoPrompt — AI Prompt Optimizer for Reduced Compute

## Overview
A full-stack web application that rewrites user prompts to be cleaner, more efficient, and lower-cost in terms of AI compute usage. Uses a local LLM (via Ollama) and the HumanDelta evaluation framework to score and visualize the environmental impact of prompt optimization.

Built for FullyHacks 2026 (CSUF hackathon) — team project.

## Status
`hackathon` — submitted and demoed at FullyHacks 2026; 32 commits; 1 star, 1 fork

## Role
Team contributor. Frontend (Next.js) and backend integration work.

> Note: Confirm exact ownership scope before resume use — verify who owned LLM pipeline vs. frontend vs. DB.

## Tech Stack

### Frontend
- Next.js (React + Tailwind CSS)

### Backend
- FastAPI (Python)
- Ollama (local LLM runner, model: `qwen2.5:1.5b`)
- HumanDelta (prompt evaluation/scoring framework)
- PostgreSQL via Neon (persistent prompt storage)

## What Was Built
- Full pipeline: user submits a prompt → Ollama rewrites it for efficiency → HumanDelta scores the improvement → result displayed with environmental impact visualization
- Local LLM integration using Ollama (avoids cloud API costs and latency during demo)
- PostgreSQL backend (Neon) for storing prompt history and comparison data
- Three-service architecture (Ollama, FastAPI backend, Next.js frontend) with documented run order

## Key Technical Challenges
- Running a local LLM reliably (Ollama serve + model pull) and connecting it to the FastAPI layer without adding latency that would break the demo
- Designing the HumanDelta scoring integration to produce meaningful, interpretable environmental impact metrics
- Coordinating a 3-service startup sequence cleanly for demo conditions

## Outcomes / Metrics
- Working end-to-end demo delivered at FullyHacks 2026
- Prompt rewriting pipeline functional with live Ollama inference
- Environmental impact visualization rendered in real time alongside rewritten prompts

## Significance for Resume
- Demonstrates awareness of AI sustainability/efficiency — a growing area of interest at major AI labs
- Shows practical LLM deployment skills (local inference, API wrapping, evaluation)
- Good talking point for roles at companies with responsible AI or green computing focus
- Relevant to: ML Engineer, AI/LLM Engineer, Full Stack Engineer roles

## Tags
`hackathon`, `llm`, `ollama`, `fastapi`, `nextjs`, `react`, `postgresql`, `python`, `local-inference`, `ai-efficiency`, `team`
