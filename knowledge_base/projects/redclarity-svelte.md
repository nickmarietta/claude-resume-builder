# Project: redClarity — Medical Lab Results Interpreter

## Overview
A full-stack web application that allows users to upload medical lab result PDFs (specifically Comprehensive Metabolic Panel reports), parses the data, and uses an LLM to explain results in plain English. Also generates doctor questions the user should ask and supports multi-language translation (Spanish, French, Vietnamese, English).

Frontend: Svelte (built by teammates). Backend: Flask + Gemini API (built by Nick).

## Status
`personal` — team project; Nick owns the backend repo (`nickmarietta/backendredClarity`, 36 commits); frontend in `thisguyblink/redClarity`

## Role
Backend developer and AI/prompt engineer. Sole owner of the Flask backend and all LLM prompt design. Teammates owned the Svelte frontend.

## Tech Stack

### Backend (Nick's ownership)
- Python / Flask (REST API)
- PyPDF2 (PDF parsing — extracts Comprehensive Metabolic Panel text)
- Google Gemini API (`gemini-2.0-flash`) via `google-genai`
- Google Cloud Translate API (Spanish, French, Vietnamese, English)
- Flask-CORS (cross-origin support for Svelte frontend)
- Deployed to Google Cloud Run (inferred from PORT env var pattern)

### Frontend (teammates)
- Svelte / SvelteKit

## What I Built / My Contributions
- Designed and implemented the full Flask backend with 7 API endpoints: file validation, PDF parsing, Gemini LLM call, and 4 translation routes
- Wrote the system-level prompts for two separate Gemini calls:
  1. Explanation prompt: instructs the model to analyze CMP lab values and return a plain-English paragraph summary of results and their significance, avoiding irrelevant information
  2. Questions prompt: instructs the model to generate 4 relevant physician questions the user should ask based on their specific results
- Integrated Google Cloud Translate to support Spanish, French, Vietnamese, and English output — making the tool accessible to non-English-speaking patients
- Parsed CMP-specific PDF structure (splitting on "COMPREHENSIVE METABOLIC PANEL" header to isolate lab values)

## Key Technical Challenges
- Prompt engineering for medical accuracy and readability: results need to be understandable to a non-medical audience without being so simplified they lose clinical relevance
- PDF parsing is brittle — extracting structured lab values from unformatted PDF text required a targeted split strategy
- Managing two sequential Gemini API calls (explanation + questions) and returning both payloads in a single response
- CORS configuration for cross-origin Svelte frontend access

## Outcomes / Metrics
- Full pipeline functional: PDF upload → lab value extraction → LLM explanation + 4 physician questions → multi-language translation
- Supports 4 languages via Google Cloud Translate (English, Spanish, French, Vietnamese)
- 36 commits in Nick's backend repo; working integration with Svelte frontend

## Significance for Resume
- Strong AI/LLM prompt engineering signal: designed system prompts to control model behavior, output format, and information scope for a sensitive domain (medical)
- Healthcare + AI intersection is high-value for ML Engineer and Full Stack roles
- Multi-language support via translation API shows API integration depth
- Good talking point: "built backend and LLM layer for a medical document interpreter — engineered prompts to produce plain-English explanations and actionable physician questions from raw lab data"
- Relevant to: ML Engineer, AI/LLM Engineer, Full Stack Engineer, health-tech roles

## Tags
`flask`, `python`, `gemini`, `llm`, `prompt-engineering`, `pdf-parsing`, `google-cloud`, `translation`, `healthcare`, `svelte`, `full-stack`, `team`, `backend-owner`
