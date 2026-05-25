<!-- profile -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=Guilherme%20Ciccarelli&fontSize=42&fontColor=58a6ff&animation=fadeIn&fontAlignY=38&desc=Data%20Scientist%20%26%20AI%20Systems%20Builder%20%E2%80%94%20S%C3%A3o%20Paulo&descAlignY=60&descColor=8b949e" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=60&lines=Turning+messy+data+into+decisions.;Building+AI+that+works+for+real+people.;From+credit+risk+to+AI+agents+%E2%80%94+12+years+in+the+data.)](https://git.io/typing-svg)

![Profile Views](https://komarev.com/ghpvc/?username=Guicicca90&color=58a6ff&style=flat-square&label=profile+views)

</div>

---

## Who I am

I spent 6 years doing credit risk analysis at a factoring company. Manual work — prospecting clients, evaluating receivables, assessing default risk from gut feeling and spreadsheets. I got bored. I knew the job could be automated. So in 2019 I co-founded **Duplify** with two friends to rebuild the entire factoring system from scratch.

That's when I started programming. 2020 — first line of Python, first ML model. I taught myself statistics, linear algebra, and machine learning to build a credit scoring system on CNPJ and receivables data using XGBoost, Random Forest, survival analysis (Kaplan-Meier, Cox proportional hazard), and rule-based scoring (ACIUM rules engine). The system worked. Getting clients was the hard part.

In 2022, while studying time series and ML with a post-doctoral researcher at Unicamp, I showed him the credit risk project. He liked it enough to offer me a Master's position. I didn't take it — bureaucracy got in the way — but the recognition confirmed I was on the right track.

In 2023, I co-founded **bee6** with four partners. We shipped real estate ML, agricultural AI, restaurant analytics, and document intelligence systems for clients across Brazil and the US. Most experiments failed. What survived is what you'll find in the repos below.

I am also the father of an autistic child — which is why I built [una-edu](https://github.com/Guicicca90/una-edu): an AI that generates fully personalized educational materials for autistic students, anchored in their hyperfocus themes.

---

## Projects

### Open source

| Project | Stack | About |
|---------|-------|-------|
| [bquant](https://github.com/Guicicca90/bquant) | Python · statsmodels · BigQuery | Quantitative research toolkit — ADF/KPSS stationarity, ARIMA, ARCH-LM volatility, FipeZAP/Selic/IPCA macro pipelines, B3/CVM data ingestion, KD-Tree spatial joins |
| [urban-space](https://github.com/Guicicca90/urban-space) | Python · scikit-learn · GeoSampa | Real estate ML — KNN property matching engine, multilevel pricing model integrating IPTU + RAIS + 10 macro indicators, PCA terrain scouting over 11M+ São Paulo parcels, IPTU lead mining |
| [solo-inteligente](https://github.com/Guicicca90/solo-inteligente) | Python · FAISS · LLM | Agricultural AI — automates the "perdigueiro" (manual land scout) process for São Paulo's 2023 densification plan; FAISS vector store over INCRA/CAR/SIGEF documents |

### Client & private work

| Project | Stack | About |
|---------|-------|-------|
| risco-credito-ml | Python · XGBoost · survival analysis | Credit risk engine for Cicor Factoring — ACIUM rule-based scoring, Kaplan-Meier survival curves, Cox proportional hazard model for default probability on Brazilian CNPJ data |
| berimbau-analytics | Python · BigQuery · Toast · ADP | Full analytics pipeline for Berimbau Brazilian Table (NYC) — integrates Toast POS, MarginEdge food costs, ADP payroll, and Resy reservations into a unified data warehouse |
| maxsuel-rag | Python · Whisper · FAISS · OpenAI | Document intelligence for a law firm — ingests PDFs, audio, video, spreadsheets; transcribes with Whisper; builds RAG pipeline for querying the full document base and generating legal filings |
| una-edu | Python · OpenAI · FastAPI · GCP | Multi-agent pipeline for autistic students: Researcher → Neuro-educational Adapter → Art Director → HTML Renderer. Print-ready A4 materials personalized by grade, hyperfocus, and ASD profile. Deployed on Cloud Run |
| guios | Python · Gemini · SQLite · Telegram | Personal AI OS — multi-agent system with three-tier memory (episodic/medium-term/long-term), 22-table personal data warehouse (maps, fitness, WhatsApp, finances), Telegram interface |

---

## Background

**2013–2019 — Cicor Factoring**
Credit risk analyst. Six years evaluating receivables and default risk by hand. Built the statistical intuition that later became the credit scoring system.

**2019–2023 — Duplify (co-founder)**
Rebuilt the entire factoring management system from zero — receivables import, payment requests, real-time credit scoring, portfolio monitoring. Deployed XGBoost/Random Forest for credit risk on CNPJ data. Survival analysis (Kaplan-Meier, Cox model) for default time-to-event modeling. Offered a Master's position at Unicamp based on this project — declined due to bureaucracy.

**2023–present — bee6 (CTO & Data Scientist)**
- **Berimbau Brazilian Table (NYC)** — restaurant analytics integrating Toast POS, MarginEdge, ADP, Resy
- **Maxsuel & Rodrigues** — document intelligence RAG for a law firm; Whisper transcription pipeline
- **Bid Brokers** — real estate KNN matching engine and pricing model
- **Solo Inteligente** — terrain scouting AI for São Paulo's 2023 urban densification plan
- **Una Edu** — adaptive education platform for autistic students

---

## Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=58a6ff)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=58a6ff)
![Google Cloud](https://img.shields.io/badge/GCP-0d1117?style=for-the-badge&logo=googlecloud&logoColor=58a6ff)
![BigQuery](https://img.shields.io/badge/BigQuery-0d1117?style=for-the-badge&logo=googlebigquery&logoColor=58a6ff)
![OpenAI](https://img.shields.io/badge/OpenAI-0d1117?style=for-the-badge&logo=openai&logoColor=58a6ff)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0d1117?style=for-the-badge&logo=scikitlearn&logoColor=58a6ff)
![pandas](https://img.shields.io/badge/pandas-0d1117?style=for-the-badge&logo=pandas&logoColor=58a6ff)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=for-the-badge&logo=fastapi&logoColor=58a6ff)
![SQLite](https://img.shields.io/badge/SQLite-0d1117?style=for-the-badge&logo=sqlite&logoColor=58a6ff)
![FAISS](https://img.shields.io/badge/FAISS-0d1117?style=for-the-badge&logoColor=58a6ff)

</div>

---

## Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Guicicca90&show_icons=true&theme=github_dark&hide_border=true&count_private=true&icon_color=58a6ff&title_color=58a6ff&include_all_commits=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Guicicca90&layout=compact&theme=github_dark&hide_border=true&title_color=58a6ff&langs_count=6" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Guicicca90&theme=github-dark-blue&hide_border=true&stroke=58a6ff&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" />

</div>

<div align="center">

<img src="https://raw.githubusercontent.com/Guicicca90/Guicicca90/output/github-contribution-grid-snake-dark.svg" alt="snake animation" />

</div>

---

## Education

**USP** — Bachelor's in Social Sciences (in progress, FFLCH)
Quantitative methods, sampling design, and fieldwork for socioeconomic research.
Co-founded the Social Research Junior Institute — ran surveys and data collection for Professor Gustavo Venturi's social impact studies.
The statistical foundation that later moved into finance, econometrics, and ML.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=100&section=footer" />

</div>
