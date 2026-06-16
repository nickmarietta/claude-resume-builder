# Project: EcoNauts — Renewable Energy Placement & Sustainability Scoring

## Overview
A full-stack interactive web application that helps users evaluate wind and solar energy installation sites using real-time weather data and machine learning predictions. Users place markers on a map and instantly receive sustainability scores and energy output predictions based on environmental and economic factors.

Built for FullyHacks 2025 (CSUF hackathon) — team of 4.

## Status
`hackathon` — built and demoed at FullyHacks 2025; 108 commits, actively developed during the event

## Role
Team contributor (team of 4). Contributed to frontend development (React/Mapbox UI) and system integration between ML backend and interactive map.

> Note: Clarify exact ownership split before finalizing resume bullets. Verified contributions: frontend marker/map interaction, Docker integration work.

## Tech Stack

### Frontend
- React (with Vite)
- Mapbox GL JS (interactive map with draggable markers)
- Tailwind CSS + DaisyUI
- Framer Motion (animations)
- Recharts (data visualization/comparison graphs)

### Backend
- FastAPI (REST API, Python 3.12)
- Machine Learning:
  - RandomForestRegressor (scikit-learn) — wind energy prediction
  - Artificial Neural Network (TensorFlow/Keras) — solar energy prediction
- pandas, numpy, joblib (data processing)
- Weather APIs: WeatherAPI, Open-Meteo, OpenWeatherMap
- pvlib (solar irradiance calculations)

### DevOps
- Docker + Docker Compose (containerized multi-service deployment)

## What Was Built
- Interactive map where users place markers to simulate wind or solar installations
- Real-time sustainability scoring combining ML energy predictions with environmental factors (emissions, land use, water use, cost, scalability)
- Two separate ML models trained for wind vs. solar prediction with feature engineering from live weather API data
- Side-by-side comparison graphs for different energy sources at a given location
- Fully Dockerized deployment for reproducibility

## Key Technical Challenges
- Integrating Docker networking so the React frontend could communicate with the FastAPI backend reliably across containers
- Feature engineering from multiple real-time weather APIs (rate limits, inconsistent schemas)
- Combining ML model outputs with multi-factor sustainability scoring into a single meaningful metric

## Outcomes / Metrics
- End-to-end ML pipeline deployed and demoed at FullyHacks 2025
- Successfully rendered real-time sustainability scores from live weather data during the hackathon demo
- Full-stack integration of 2 ML models + 3 weather APIs + interactive map UI completed within hackathon timeframe

## Significance for Resume
- Demonstrates ML deployment in a real product context (not just notebook/model training)
- Shows full-stack ownership: data pipeline → API → interactive UI → containerized deployment
- Strong talking point for sustainability/climate-tech roles and for general ML Engineer positions
- Relevant to: ML Engineer, Full Stack Engineer, Data Science roles

## Tags
`hackathon`, `ml`, `tensorflow`, `scikit-learn`, `react`, `fastapi`, `docker`, `mapbox`, `python`, `full-stack`, `energy`, `sustainability`, `team`
