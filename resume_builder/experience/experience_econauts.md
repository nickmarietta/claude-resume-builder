---
name: experience_econauts
description: EcoNauts (GreenPlacement) hackathon — 1st place Sustainability at FullyHacks 2025; Nick owned FastAPI routing layer and Docker Compose; contributing: frontend metrics UI; team of 4
metadata:
  type: experience
---

# Experience: EcoNauts — Renewable Energy Placement Tool
## 2025 — Team Hackathon Project (4 people), FullyHacks 2025 — 1st Place, Sustainability Category

### Cross-Project Section
EcoNauts is Nick's most visible external credential: a team award from a named hackathon. His role was backend integration and containerization — he did not build the ML models or weather APIs, but he built the layer that made them accessible to the frontend. The award is a team award; always frame it as such. The correct claim is "won 1st place in the Sustainability category at FullyHacks 2025" with a clear team-of-4 attribution.

**CL framing:** Use EcoNauts to show real-world API/ML model integration experience, Docker/containerization competence, and the ability to ship award-winning software on a cross-functional team. The 1st place result is strong social proof for any new-grad application.

---

### Achievement EN-01: FastAPI Routing Layer (ML → Frontend)
**Source:** marietta2025_econauts.md
**Paper:** N/A — hackathon project
**User's role:** Sole contributor (FastAPI routing layer)
**Status:** Hackathon — 1st place, Sustainability, FullyHacks 2025

**Context:** The ML models (RandomForestRegressor for wind, ANN for solar) produced predictions, but without a routing layer those predictions couldn't reach the React frontend. Nick built the FastAPI layer that served model outputs to the UI as real-time API responses.

**Bullet variants:**
- **2L:** Built the full FastAPI routing layer connecting ML model outputs (wind/solar energy predictions) to the React frontend, enabling real-time sustainability scoring for a team that won 1st place in the Sustainability category at FullyHacks 2025.
- **3L:** Sole-built the FastAPI routing layer serving as the integration bridge between two ML model backends — a RandomForestRegressor for wind prediction and an ANN for solar — and the React/Mapbox frontend, enabling real-time sustainability scores and energy output data to flow into the user-facing UI for a 1st-place FullyHacks 2025 project.
- **1L:** Built FastAPI routing layer connecting ML outputs to React frontend; team won 1st place at FullyHacks 2025.

**Key skills:** FastAPI, Python, REST API, ML model integration, backend routing
**ATS keywords:** FastAPI, REST API, machine learning integration, Python, backend, API routing
**Reframing notes:** ML/AI — emphasize ML model serving and integration architecture. Full Stack — emphasize API layer and frontend integration. Defense — mention if JD asks for API or systems integration experience.

---

### Achievement EN-02: Docker Compose Orchestration
**Source:** marietta2025_econauts.md
**Paper:** N/A — hackathon project
**User's role:** Sole contributor (Docker Compose authorship)
**Status:** Hackathon — 1st place, Sustainability, FullyHacks 2025

**Context:** A multi-service architecture (React frontend + FastAPI backend) requires reliable cross-container networking to function in a demo environment. Nick authored the docker-compose.yml that wired the services together and ensured startup reliability.

**Bullet variants:**
- **2L:** Wrote the Docker Compose configuration orchestrating cross-container communication between the React frontend and FastAPI backend, enabling reliable multi-service startup for a hackathon demo environment.
- **3L:** Authored the `docker-compose.yml` orchestrating cross-container networking between the React/Vite frontend and FastAPI backend services, ensuring reliable startup sequencing and inter-container communication within a multi-service architecture under hackathon demo constraints.
- **1L:** Wrote Docker Compose config orchestrating cross-container communication between React frontend and FastAPI backend.

**Key skills:** Docker, Docker Compose, containerization, DevOps, multi-service architecture
**ATS keywords:** Docker, Docker Compose, containerization, multi-service, DevOps
**Reframing notes:** Full Stack — strong fit (containerization). Defense — relevant if JD mentions Docker or deployment. ML/AI — secondary.

---

### Achievement EN-03: Frontend Metric Display UI (Contributing)
**Source:** marietta2025_econauts.md
**Paper:** N/A — hackathon project
**User's role:** Contributing (alongside primary frontend teammate)
**Status:** Hackathon — 1st place, Sustainability, FullyHacks 2025

**Context:** The sustainability score and energy output visualizations needed to be accurate and visually connected to the map. Nick contributed the metric display components and validated Mapbox coordinate accuracy to ensure map markers fed the correct geographic data to the ML models.

**Bullet variants:**
- **2L:** Contributed to the React metric display UI — built sustainability score visualizations and validated Mapbox coordinate accuracy to ensure map marker positions fed correctly into the ML inference layer.
- **3L:** Contributed to the React metric display interface using Recharts — built sustainability score and energy output visualizations — and separately validated Mapbox GL coordinate accuracy to ensure location markers fed correct geographic data to the ML inference models throughout the demo.
- **1L:** Contributed React metric display UI and validated Mapbox coordinates for ML model input accuracy.

**Key skills:** React, Recharts, Mapbox GL, data visualization, frontend (contributing)
**ATS keywords:** React, data visualization, Mapbox, Recharts, frontend
**Reframing notes:** Full Stack — use as supporting bullet, not lead. Hedge clearly ("contributed to"). ML/AI — mention Mapbox coordinate validation as ML input accuracy concern. Defense — omit.

**Overclaiming warning:** Do NOT say "built the frontend" or omit "contributed to." Primary frontend was a teammate. Nick's specific contributions were metric display components and coordinate validation.

---

### Achievement EN-04: 1st Place Award — Project Integration
**Source:** marietta2025_econauts.md
**Paper:** N/A — hackathon project
**User's role:** Team contributor
**Status:** Hackathon — 1st place, Sustainability, FullyHacks 2025

**Context:** Framing bullet for the full project — captures the award result and the scope of system integration. Use as a project-level summary bullet or in project header lines, not as a standalone technical achievement.

**Bullet variants:**
- **2L:** Helped deliver full-stack integration of 2 ML models, 3 weather APIs, and an interactive Mapbox UI within hackathon constraints — team won 1st place in the Sustainability category at FullyHacks 2025 (team of 4).
- **3L:** Contributed to the full-stack integration of two ML models (RandomForestRegressor + ANN), three weather data APIs, and an interactive Mapbox-based scoring UI — delivered within hackathon constraints — as the team won 1st place in the Sustainability category at FullyHacks 2025 with a team of four engineers.
- **1L:** Contributed to 1st-place FullyHacks 2025 project integrating 2 ML models, 3 weather APIs, and a Mapbox UI.

**Key skills:** System integration, full-stack, team collaboration, hackathon execution
**ATS keywords:** full-stack, team project, machine learning, hackathon, award
**Reframing notes:** Use as a header/summary bullet for the EcoNauts project entry on the resume. Combine with EN-01 or EN-02 for the technical lead bullet.

---

### Provenance Guardrails (All EN Achievements)
- Award framing: "won 1st place in the Sustainability category at FullyHacks 2025" — always include "team of 4"
- Nick's sole ownership: FastAPI routing layer, `docker-compose.yml`
- Nick's contributing work: frontend metric display, Mapbox coordinate validation
- Do NOT claim: ML models (RandomForest, ANN, TensorFlow/scikit-learn), weather API integration, feature engineering, primary frontend — all teammates
