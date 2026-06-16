# Configuration

> Edit this file with your personal details. Every skill reads this file.

---

## Personal Info

- **Name:** Nicklaus Marietta
- **Degree suffix:** B.S. Computer Science, California State University Fullerton — May 2026
- **Email:** nickmarietta@live.com
- **Phone:** +1 951-768-7087
- **Location:** Corona, CA
- **LinkedIn:** https://www.linkedin.com/in/nicklaus-marietta/
- **Google Scholar:** N/A
- **ORCID:** N/A
- **Website:** nickmarietta.tech

---

## Document Preferences

- **Resume pages:** 1
- **CV pages:** 2
- **Resume bullet variant:** 2L (all variable bullets are 2-line)
- **CV bullet variant:** 2L/3L mix
- **Skills config (resume):** 5-4-6-5 (20 items, 4 groups)
- **Skills config (CV):** 5-4-6-5 (same grouping, expanded descriptions allowed)


---

## Skills Reference

Used by all generation skills to populate the Skills section. Do not reorder groups without updating Skills config above.

| Group | Label | Items |
|-------|-------|-------|
| 1 | Languages | Python, JavaScript, TypeScript, C++, Java |
| 2 | AI/ML | TensorFlow, NumPy, Gemini API, scikit-learn |
| 3 | Web / Frameworks | React, Next.js, SvelteKit, Flask, FastAPI, Node.js |
| 4 | Tools & Infra | Git, Docker, Google Cloud Platform, AWS, PostgreSQL |

---

## Provenance Flags

Track the status of your projects. Skills check this table before every output.

| Item | Status | Correct Framing |
|------|--------|----------------|
| Chess Tutor | beta — local deployment, real users | "beta with real users" — never say "deployed" or "production" |
| EcoNauts (GreenPlacement) | hackathon — 1st place, Sustainability category, FullyHacks 2025 | "won 1st place in the Sustainability category at FullyHacks 2025" |
| EcoPrompt | hackathon — no award; 30% token reduction metric | "resulted in 30% reduction in token usage" — never claim award |
| redClarity | personal team project | "contributed backend and LLM layer" — never claim full ownership |
| Nuri | personal team project | "implemented app logic and connected Figma designs" — never claim design work |
| FullyHacks 2024 LLP | hackathon — no award | "built for FullyHacks 2024" — do not imply placement |
| SignalML (Raytheon) | professional — sponsored capstone, patent contribution | "contributed to patent" — never say "filed" or "awarded" solo |

---

## KB Corrections Log

Verified errors to never re-introduce. Add entries as you catch mistakes.

| Correction | Details |
|-----------|---------|
| Name spelling | It's "Nicklaus Marietta" — never "Nicklaus Mareitta" or other variants |

---

## Role Types

| Role Name | Target Employers | Tier | Bundle File |
|-----------|-----------------|------|-------------|
| ML / AI Engineer | AI labs, tech companies, defense R&D | 1 | bundle_ml_ai.md |
| Full Stack Engineer | Tech companies, startups, health-tech | 2 | bundle_fullstack.md |
| Defense / Aerospace | Raytheon, L3Harris, Northrop, Leidos, SAIC, Aerospace Corp | 2 | bundle_defense.md |

**Tier guide:** 1 = strongest evidence, full portfolio | 2 = strong with targeted emphasis | 3 = viable with careful framing

---

## Role-Type Decision Tree

| If JD mentions... | Primary profile | Secondary (hybrid) |
|-------------------|----------------|-------------------|
| machine learning, LLM, AI, model training, inference | ML / AI Engineer | Full Stack Engineer |
| full stack, frontend, backend, React, web app, SaaS | Full Stack Engineer | ML / AI Engineer |
| signal processing, defense, aerospace, DoD, clearance, embedded | Defense / Aerospace | ML / AI Engineer |
| new grad, entry level, rotation program | Match to JD domain above | -- |

---

## FIXED Sections

List template sections that should NEVER be modified during generation.

- Header block (name, contact, links)
- Education (CSUF B.S. CS, May 2026)
Skills section (populated from Skills Reference table above — items never fabricated)
---

## Output Rules

- **Target length:** 1-page resume for all New Grad applications
- **Email in all outputs:** nickmarietta@live.com
- **Resume package:** 1 page + 1-page cover letter
- **CV package:** 2 pages + 1-page cover letter
- **Output .tex files ONLY** — user compiles locally
- **No publications section** — replace with Projects section on all outputs
- **Projects over papers:** All generation skills should treat `knowledge_base/projects/` as the primary source material, equivalent to what `knowledge_base/papers/` is in the default kit
- **Seniority framing:** Always frame as a new grad / recent graduate. Never use senior-level ownership verbs for team projects where Nick's role was a contributor.
