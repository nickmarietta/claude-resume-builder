---
name: marietta2025_econauts
description: EcoNauts/GreenPlacement hackathon — 1st place Sustainability at FullyHacks 2025; Nick owned FastAPI routing layer and Docker Compose; contributed frontend metrics UI; team of 4
metadata:
  type: project
---

# EcoNauts — Renewable Energy Placement & Sustainability Scoring

## Metadata
- **Project:** EcoNauts (also known as GreenPlacement)
- **Contributors:** **Nicklaus Marietta** + 3 teammates
- **Year:** 2025 (FullyHacks 2025, CSUF hackathon)
- **Type:** Team hackathon project (4 people)
- **Status:** Hackathon — 1st place, Sustainability category, FullyHacks 2025
- **Correct framing:** "won 1st place in the Sustainability category at FullyHacks 2025" (per config.md)

## Methods & Tools
- **API layer:** FastAPI (Python 3.12) — Nick built all routing after ML team delivered model outputs
- **Containerization:** Docker + Docker Compose — Nick wrote the `docker-compose.yml`
- **Frontend (contributed):** React (Vite), Mapbox GL JS, Tailwind CSS + DaisyUI, Recharts, Framer Motion — Nick built metric display UI and ensured map coordinates sent to model were accurate
- **ML models (teammates):** RandomForestRegressor (scikit-learn) for wind prediction; ANN (TensorFlow/Keras) for solar prediction
- **Weather APIs (teammates):** WeatherAPI, Open-Meteo, OpenWeatherMap; pvlib for solar irradiance
- **Data processing (teammates):** pandas, numpy, joblib

## Key Results
1. Won 1st place in the Sustainability category at FullyHacks 2025 (team award)
2. Built the full FastAPI routing layer connecting ML model outputs to the frontend — wired after teammates delivered accurate model metrics
3. Wrote the `docker-compose.yml` enabling reliable cross-container communication between React frontend and FastAPI backend
4. Contributed to frontend metric display UI (sustainability scores, energy output visualization) and validated map coordinate accuracy before coordinates were passed to ML models
5. Full-stack integration of 2 ML models + 3 weather APIs + interactive Mapbox UI delivered within hackathon timeframe

## Novelty Claims
- Real-time sustainability scoring combining ML energy predictions with multi-factor environmental metrics (emissions, land use, water use, cost, scalability) in a single interactive map UI
- Two separate domain-specific ML models (wind: RF; solar: ANN) served through a single FastAPI layer

## Collaboration & Scope
- **Team of 4 — split:**
  - Nick: FastAPI routing layer, Docker Compose, frontend metric UI (contributing), map coordinate validation
  - 2 teammates: ML models (scikit-learn, TensorFlow), weather API integrations, feature engineering
  - 1 teammate: primary frontend (React/Mapbox/Tailwind); Nick contributed alongside
- **Nick's sole ownership:** FastAPI routes, `docker-compose.yml`
- **Nick's contributing work:** Frontend metrics display, map coordinate accuracy

## Provenance Notes
- **Publication status:** N/A — hackathon project
- **Safe to claim (full ownership):** FastAPI routing layer; Docker Compose authorship; 1st place award (team)
- **Safe to claim (contributing):** Frontend metric display UI; map coordinate validation
- **Needs hedging:** Any frontend claim — use "contributed to" or "helped build"
- **Do NOT claim:** ML model development (RandomForest, ANN, TensorFlow/scikit-learn); weather API integration; feature engineering — those were teammates

## Resume Bullet Seeds
1. Routed the full FastAPI backend layer connecting ML model outputs (wind/solar energy predictions) to the React frontend, enabling real-time sustainability scoring for a 1st-place FullyHacks 2025 project
2. Wrote the Docker Compose configuration orchestrating cross-container communication between the React frontend and FastAPI backend across the multi-service architecture
3. Contributed to the React metric display UI and validated Mapbox coordinate accuracy to ensure map marker positions were correctly passed to the ML inference layer
4. Helped integrate two ML models (RandomForestRegressor for wind, ANN for solar) via FastAPI into a unified scoring API serving real-time predictions from live weather data
5. Built and containerized the API layer for an award-winning sustainability tool — team won 1st place in the Sustainability category at FullyHacks 2025 (team of 4)
