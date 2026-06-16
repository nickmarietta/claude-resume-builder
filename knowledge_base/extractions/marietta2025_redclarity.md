---
name: marietta2025_redclarity
description: redClarity medical lab results interpreter — Nick sole-owned Flask backend, Gemini prompt engineering (2 system prompts), PDF parsing, 4-language translation; teammates owned Svelte frontend
metadata:
  type: project
---

# redClarity — Medical Lab Results Interpreter

## Metadata
- **Project:** redClarity (backend repo: `nickmarietta/backendredClarity`; frontend: `thisguyblink/redClarity`)
- **Contributors:** **Nicklaus Marietta** (backend) + teammates (Svelte frontend)
- **Year:** ongoing (personal team project)
- **Type:** Personal team project
- **Status:** Personal — no hackathon, no award
- **Correct framing:** "contributed backend and LLM layer" — never claim full product ownership (per config.md)

## Methods & Tools
- **Backend framework:** Python / Flask (REST API — 7 endpoints)
- **LLM:** Google Gemini API (`gemini-2.0-flash`) via `google-genai` — 2 separate system prompt calls
- **PDF parsing:** PyPDF2 — split on "COMPREHENSIVE METABOLIC PANEL" header to isolate lab values from unstructured PDF text
- **Translation:** Google Cloud Translate API — English, Spanish, French, Vietnamese
- **Cross-origin:** Flask-CORS (Svelte frontend integration)
- **Deployment:** Google Cloud Run (inferred from PORT env var pattern)
- **Frontend (teammates):** Svelte / SvelteKit

## Key Results
1. Built full Flask backend with 7 API endpoints: file validation, PDF parsing, Gemini LLM call, and 4 translation routes
2. Engineered 2 system-level Gemini prompts: (1) explanation prompt — analyzes CMP lab values and returns a plain-English paragraph summary avoiding irrelevant clinical detail; (2) questions prompt — generates 4 physician questions tailored to the user's specific results
3. Integrated Google Cloud Translate to deliver output in 4 languages (English, Spanish, French, Vietnamese), making the tool accessible to non-English-speaking patients
4. Implemented targeted PDF parsing strategy splitting on the CMP report header to reliably extract structured lab values from unformatted PDF text
5. Managed two sequential Gemini API calls and returned both payloads (explanation + questions) in a single response to the frontend
6. 36 commits in Nick's backend repo; full working integration with Svelte frontend

## Novelty Claims
- Medical domain prompt engineering: prompts designed to balance clinical accuracy with plain-English accessibility for non-medical users
- Two-call Gemini architecture producing both an explanation and actionable physician questions from the same lab data in a single backend response

## Collaboration & Scope
- **Nick's sole ownership:** Full Flask backend — all 7 endpoints, both Gemini system prompts, PDF parsing logic, Google Cloud Translate integration, Flask-CORS config, Cloud Run deployment
- **Teammates' ownership:** Svelte/SvelteKit frontend
- **Shared:** Overall product concept and frontend↔backend integration

## Provenance Notes
- **Publication status:** N/A — personal project
- **Safe to claim (full ownership):** Flask backend (7 endpoints), both Gemini system prompts, PDF parsing, Google Cloud Translate integration, Cloud Run deployment
- **Needs hedging:** Full product — use "contributed backend and LLM layer" not "built redClarity" when referring to the whole app
- **Do NOT claim:** Svelte frontend — teammates built it; do not claim full product ownership

## Resume Bullet Seeds
1. Built the Flask backend and LLM layer for a medical document interpreter — engineered system prompts for Gemini to produce plain-English explanations of CMP lab results and generate 4 tailored physician questions per upload
2. Designed two Gemini API system prompts for a medical domain: one to summarize lab values accessibly for non-clinical users, one to generate patient-specific follow-up questions for their physician
3. Integrated Google Cloud Translate to deliver LLM output in English, Spanish, French, and Vietnamese — expanding accessibility for non-English-speaking patients
4. Implemented PDF parsing for Comprehensive Metabolic Panel reports using PyPDF2 with a targeted header-split strategy to reliably extract lab values from unstructured text
5. Architected a 7-endpoint Flask REST API managing file validation, PDF extraction, two sequential Gemini calls, and 4 translation routes for a health-tech team project
