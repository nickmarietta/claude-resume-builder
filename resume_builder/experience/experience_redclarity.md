---
name: experience_redclarity
description: redClarity medical lab results interpreter — Nick sole-owned Flask backend (7 endpoints), Gemini prompt engineering (2 system prompts), PDF parsing, 4-language Google Cloud Translate; BeachHacks hackathon, no award
metadata:
  type: experience
---

# Experience: redClarity — Medical Lab Results Interpreter
## 2025 — Team Hackathon Project, BeachHacks — No Award

### Cross-Project Section
redClarity is Nick's strongest backend-plus-LLM project: sole ownership of a 7-endpoint Flask REST API, two system-level Gemini prompts, PDF parsing, and 4-language translation — all for a medical domain. The healthcare context and multilingual accessibility angle give this project differentiated positioning for health-tech roles and any role requiring LLM prompt engineering with real-world consequences. The two-call Gemini architecture (explanation + physician questions in one response) is the most architecturally interesting claim.

**CL framing:** Use redClarity to show medical-domain LLM prompt engineering, Flask REST API ownership, PDF document processing, and accessibility focus (4-language output). It is the project most likely to resonate with health-tech, AI tooling, or developer tools companies that value real-world application of LLMs.

**Correct framing reminder:** "contributed backend and LLM layer" when referring to the full product — teammates own the Svelte frontend. Never imply an award; correct framing is "built for BeachHacks."

---

### Achievement RC-01: 7-Endpoint Flask REST Backend
**Source:** marietta2025_redclarity.md
**Paper:** N/A — personal project
**User's role:** Sole contributor (full backend)
**Status:** Hackathon — BeachHacks, no award

**Context:** The backend needed to handle file validation, PDF extraction, two sequential LLM calls, and four language-specific translation routes — all as a clean REST API callable from the Svelte frontend. Nick designed and built all 7 endpoints.

**Bullet variants:**
- **2L:** Built the full Flask REST backend for a medical document interpreter — architected 7 endpoints covering file validation, PDF parsing, LLM inference, and 4 translation routes for a health-tech team project.
- **3L:** Sole-architected and built a 7-endpoint Flask REST API for a medical document interpreter: endpoints handling file upload and validation, PDF extraction, two sequential Gemini LLM calls, and four language-specific translation routes, integrated with a teammate-built Svelte frontend via Flask-CORS.
- **1L:** Sole-built Flask backend (7 endpoints) — file validation, PDF parsing, Gemini LLM, and 4 translation routes.

**Key skills:** Python, Flask, REST API design, Flask-CORS, backend architecture, health-tech
**ATS keywords:** Flask, REST API, Python, backend, API design, health-tech, medical
**Reframing notes:** Full Stack — lead bullet for redClarity. ML/AI — secondary to RC-02 (prompt engineering). Defense — omit.

---

### Achievement RC-02: Gemini Prompt Engineering — Medical Domain
**Source:** marietta2025_redclarity.md
**Paper:** N/A — personal project
**User's role:** Sole contributor (both system prompts)
**Status:** Hackathon — BeachHacks, no award

**Context:** Medical lab results (CMP panels) contain clinical jargon inaccessible to non-clinical users. Nick engineered two system-level Gemini prompts: one to explain the results in plain English, one to generate 4 physician follow-up questions tailored to the user's specific values — requiring medical accuracy with non-technical accessibility.

**Bullet variants:**
- **2L:** Engineered 2 Gemini system prompts for a medical domain: one summarizing CMP lab values in plain English for non-clinical users, one generating 4 tailored physician follow-up questions per upload.
- **3L:** Engineered 2 system-level Gemini prompts for a medical interpretation use case: an explanation prompt converting Comprehensive Metabolic Panel lab values into plain-English patient summaries, and a question-generation prompt producing 4 physician follow-up questions individually tailored to each upload's specific results.
- **1L:** Engineered 2 Gemini system prompts for a medical domain: CMP lab summarizer and physician question generator.

**Key skills:** Prompt engineering, Gemini API, Google Gemini, LLM, medical AI, system prompts
**ATS keywords:** prompt engineering, Gemini API, LLM, system prompts, medical AI, Google AI
**Reframing notes:** ML/AI — strongest claim in redClarity; lead with this. Full Stack — secondary to RC-01. Defense — mention if JD involves AI or NLP.

---

### Achievement RC-03: Google Cloud Translate — 4-Language Accessibility
**Source:** marietta2025_redclarity.md
**Paper:** N/A — personal project
**User's role:** Sole contributor
**Status:** Hackathon — BeachHacks, no award

**Context:** Non-English-speaking patients often struggle to access medical explanations. Integrating Google Cloud Translate to deliver LLM output in English, Spanish, French, and Vietnamese expanded the tool's accessibility across a broader patient population.

**Bullet variants:**
- **2L:** Integrated Google Cloud Translate to deliver LLM output in English, Spanish, French, and Vietnamese — expanding accessibility for non-English-speaking patients across 4 dedicated translation endpoints.
- **3L:** Integrated the Google Cloud Translate API to deliver LLM-generated explanations and physician questions in English, Spanish, French, and Vietnamese, building 4 translation-specific endpoints to serve non-English-speaking patients and broaden the tool's accessibility across language demographics.
- **1L:** Integrated Google Cloud Translate delivering LLM output in 4 languages for non-English-speaking patients.

**Key skills:** Google Cloud Translate, Flask, API integration, multilingual, accessibility, Python
**ATS keywords:** Google Cloud, translation API, multilingual, accessibility, Flask, API integration
**Reframing notes:** Full Stack — good differentiation bullet (accessibility + cloud API). ML/AI — secondary. Defense — omit.

---

### Achievement RC-04: PDF Parsing for Medical Reports
**Source:** marietta2025_redclarity.md
**Paper:** N/A — personal project
**User's role:** Sole contributor
**Status:** Hackathon — BeachHacks, no award

**Context:** CMP lab reports are unstructured PDFs with inconsistent formatting. Nick implemented a header-split parsing strategy using PyPDF2 that reliably isolates the structured lab values section regardless of what precedes it in the document.

**Bullet variants:**
- **2L:** Implemented a targeted PDF parsing strategy using PyPDF2 with a header-split approach on "COMPREHENSIVE METABOLIC PANEL" to reliably extract structured lab values from unformatted medical PDF text.
- **3L:** Implemented a targeted PDF parsing pipeline using PyPDF2 with a document-structure-aware header-split strategy — splitting on the "COMPREHENSIVE METABOLIC PANEL" header — to reliably isolate and extract structured CMP lab values from unformatted, inconsistently-laid-out medical PDF reports.
- **1L:** Implemented PDF parsing with PyPDF2 and CMP header-split to reliably extract structured lab values from medical PDFs.

**Key skills:** PyPDF2, PDF parsing, Python, document processing, text extraction
**ATS keywords:** PDF parsing, PyPDF2, document processing, text extraction, Python
**Reframing notes:** Full Stack — secondary to RC-01. ML/AI — mention as document processing input to LLM pipeline. Defense — omit.

---

### Achievement RC-05: Two-Call Gemini Architecture
**Source:** marietta2025_redclarity.md
**Paper:** N/A — personal project
**User's role:** Sole contributor
**Status:** Hackathon — BeachHacks, no award

**Context:** Running two Gemini calls (explanation + questions) and returning both payloads in a single response minimizes frontend round trips and delivers a coherent atomic result — a deliberate architectural decision over a two-request client model.

**Bullet variants:**
- **2L:** Managed two sequential Gemini API calls within a single backend response — explanation and physician questions generated together — minimizing frontend round trips and delivering both outputs atomically per upload.
- **3L:** Architected a two-call Gemini inference pipeline that executes both system prompts sequentially within a single backend response cycle, packaging explanation and physician question outputs together atomically to minimize frontend round-trip overhead and simplify client-side state management.
- **1L:** Architected two-call Gemini pipeline delivering explanation + physician questions in one atomic API response.

**Key skills:** Gemini API, API design, LLM architecture, Flask, Python, sequential inference
**ATS keywords:** Gemini API, LLM, API architecture, sequential inference, Flask, Python
**Reframing notes:** ML/AI — strong supporting detail for Gemini/prompt engineering story. Full Stack — mention as API design decision. Defense — omit.

---

### Provenance Guardrails (All RC Achievements)
- Nick's ownership: full Flask backend (all 7 endpoints), both Gemini system prompts, PDF parsing, Google Cloud Translate, Cloud Run deployment
- Do NOT claim: Svelte/SvelteKit frontend — teammates built it
- Do NOT claim full product ownership — use "contributed backend and LLM layer" for product-level framing
- Correct framing: "built for BeachHacks" or "health-tech hackathon project" — never claim award
- Do NOT say "deployed" or imply production status
- Deployment: Cloud Run inference is acceptable to mention (inferred from PORT pattern); do not overstate deployment scale
