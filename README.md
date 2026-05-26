# Mahir H. Patel

**Mathematics @ UBC** · Building things at the intersection of AI systems, quantitative finance, and full-stack engineering.

I work closest to the data and model layer — designing ML pipelines, multi-agent AI architectures, and production backend systems. Currently studying stochastic processes and linear programming, which feeds directly into how I think about system design and algorithm behaviour.

---

## What I've Built

### [MarketMind](https://github.com/mahir-patel/marketmind) — Multi-Agent AI Financial Analysis Platform
The most technically complex thing I've shipped. A production-grade microservices system (12 containerized services, Docker + Kubernetes) that streams real-time OHLCV data at 1-second tick frequency via MQTT → Redis → GraphQL WebSocket into a React dashboard.

The core is a LangGraph-orchestrated multi-agent pipeline — 4 specialist agents powered by Claude API — that combines RAG over ChromaDB with SuperTrend + KNN trend classification to generate institutional-grade research notes with entry/stop/target levels. The quant engine computes 40+ metrics: Hurst exponent, VaR/CVaR at 95–99% confidence, Sharpe/Sortino, beta/alpha vs. SPY, max drawdown. Five heterogeneous databases (PostgreSQL, MongoDB, ChromaDB, Redis, Snowflake) tied together with Kafka event streaming.

`Python` `FastAPI` `LangGraph` `LangChain` `Claude API` `RAG` `ChromaDB` `Apache Kafka` `Redis` `PostgreSQL` `Snowflake` `Docker` `Kubernetes` `React` `TypeScript`

---

### [TrailSafe](https://github.com/umang-bhavsar/trailsafe/tree/mahir_1) — Hiking Safety Mobile App
Cross-platform React Native app with real-time trail discovery, Google Maps route previews, and an AI safety scoring system (OpenRouter AI) that evaluates trail risk dynamically based on weather, sunset timing, and hazard reports. Implemented a check-in system with automated overdue alerts via Supabase Edge Functions and live GPS breadcrumb tracking. CI/CD via Jenkins + EAS Build.

`React Native` `TypeScript` `Expo` `Supabase` `OpenRouter AI` `Google Maps API` `Jenkins`

---

### [StreamVault](https://stream-vault-eight.vercel.app/login) — Streaming Discovery Platform
Full-stack platform for discovering what's streaming across 100+ countries. Built the backend with Node.js/Express, JWT auth, and TMDB API integration. Modelled the PostgreSQL schema for efficient streaming availability caching. Deployed on Vercel + Railway.

`Next.js` `Node.js` `PostgreSQL` `Supabase` `REST APIs` `Tailwind CSS`

---

### Fraud Detection System — ML Classification Pipeline
XGBoost classifier on imbalanced financial transaction data with an 85% recall rate. Used SHAP for model interpretability and integrated Gemini AI to translate statistical outputs into human-readable explanations. Built as a complete pipeline from feature engineering through real-time scoring.

`Python` `XGBoost` `Scikit-learn` `SHAP` `Pandas` `NumPy` `Flask`

---

## Technical Depth

Where I spend most of my time, ranked by depth:

- **ML & Quant** — Scikit-learn, XGBoost, NumPy, Pandas, SciPy, SHAP, statistical modelling, risk metrics
- **GenAI / LLM Systems** — LangChain, LangGraph, RAG pipelines, prompt engineering, vector databases, Claude API
- **Backend & Data** — FastAPI, PostgreSQL, Redis, Kafka, REST/GraphQL, Docker, Kubernetes
- **Languages** — Python (primary), TypeScript, SQL, Java, R, C++

---

## Background

Studying Mathematics at UBC (2023–2027). The degree isn't decorative — coursework in stochastic processes, probability theory, and linear programming directly informs how I approach ML system design and algorithm selection. I find the formal rigour useful for reasoning about model behaviour rather than just running things and seeing what sticks.

Previously interned at a certified Odoo partner (Skyscend) doing Python automation and SQL pipeline work.

---

<p align="left">
  <a href="mailto:mahirhp11@gmail.com">mahirhp11@gmail.com</a> ·
  <a href="https://www.linkedin.com/public-profile/settings/?trk=d_flagship3_profile_self_view_public_profile&lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BuRDALV0DR%2Bm6syYBnkExEw%3D%3D">LinkedIn</a> ·
  Vancouver, BC
</p>
