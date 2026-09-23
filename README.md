<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:22D3C7&height=200&section=header&text=RUDRA%20SHARMA&fontSize=52&fontColor=E2F5F3&fontAlignY=38&desc=AI%20%C3%97%20DATA%20%C3%97%20SYSTEMS&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="header" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3200&pause=1100&color=22D3C7&center=true&vCenter=true&width=650&lines=Architecting+production+RAG+%26+multi-agent+systems;Building+distributed+data+pipelines+on+Spark+%2F+Databricks;Shipping+FastAPI+services+backed+by+PostgreSQL+RLS;Engineer+the+environment+in+which+AI+writes+code.)](https://rudrasharma3.github.io/Portfolio/)

<p>
  <a href="https://rudrasharma3.github.io/Portfolio/"><img src="https://img.shields.io/badge/PORTFOLIO-rudrasharma.dev-0F172A?style=for-the-badge&logo=firefox&logoColor=22D3C7" /></a>
  <a href="https://freelance-kappa-orpin.vercel.app/"><img src="https://img.shields.io/badge/CLIENT_WORK-live_services-0F172A?style=for-the-badge&logo=vercel&logoColor=22D3C7" /></a>
  <a href="https://www.linkedin.com/in/rudra-sharma-3508a227b"><img src="https://img.shields.io/badge/LINKEDIN-rudra--sharma-0F172A?style=for-the-badge&logo=linkedin&logoColor=0A66C2" /></a>
  <a href="mailto:rudrasharma93511@gmail.com"><img src="https://img.shields.io/badge/EMAIL-say_hello-0F172A?style=for-the-badge&logo=gmail&logoColor=D14836" /></a>
</p>

<sub>Jaipur, India · B.Tech CS (AI/ML), UPES Dehradun · Azure AI Engineer Associate · Open to AI & Data Engineering roles</sub>

</div>

<br/>

## → System Overview

I design and ship **AI-native backend systems** — retrieval pipelines, multi-agent orchestration, and the data infrastructure underneath them. My work sits at the intersection of three layers:

```
┌───────────────────────────────────────────────┐
│  DATA LAYER      Spark · Databricks · Delta    │
│  AI LAYER        RAG · Qdrant · BM25 · LLMs    │
│  SYSTEMS LAYER   FastAPI · PostgreSQL · Agents │
└───────────────────────────────────────────────┘
```

> *"Don't just use AI to write code — engineer the environment in which AI writes code."*

That's the principle behind **AI-OS**, my repo-native operating layer for agentic development, and it shapes how I approach every system below: contracts before code, verification before shipping.

<br/>

## → Currently Building

| | |
|---|---|
| 🧠 | **AI-OS** — a manager/worker multi-agent topology that negotiates interface contracts before any code generation begins, with a canonical `AGENTS.md` and gated, rule-checked promotion of lessons into repo memory |
| ⚡ | **VoxContextEngine** — a hybrid retrieval engine fusing dense vector search (Qdrant + `all-MiniLM-L6-v2`) with sparse BM25, wrapped in an automated hallucination-verification harness |

<br/>

## → Stack

<div align="center">

**AI / ML**
<br/>
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

**Data Engineering**
<br/>
![Apache Spark](https://img.shields.io/badge/-Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/-Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Backend & Cloud**
<br/>
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/-Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

**Interfaces**
<br/>
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</div>

<br/>

## → Featured Systems

<table>
<tr>
<td width="50%" valign="top">

**🧠 [AI-OS](https://github.com/RudraSharma3)**
<br/>Repository-native operational layer for agentic engineering.
- Canonical `AGENTS.md` with thin provider adapters (`CLAUDE.md`, `GEMINI.md`, `CODEX.md`)
- Gated self-modification — candidate lessons are rule-checked before promotion to repo memory
- Manager/worker topology that locks interface contracts before generation

`Python` `MCP` `Agent Protocols` `Git`

</td>
<td width="50%" valign="top">

**⚡ [VoxContextEngine](https://rudrasharma3.github.io/Portfolio/)**
<br/>Production hybrid-RAG platform with hallucination defense.
- Dense retrieval (Qdrant + `all-MiniLM-L6-v2`) fused with sparse BM25
- Automated verification harness — 100% safety-run completeness on hallucination tests
- Async FastAPI serving layer, containerized

`Python` `FastAPI` `Qdrant` `Docker` `BM25`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🧹 [DataPurge Studio](https://freelance-kappa-orpin.vercel.app/)**
<br/>Async multi-tenant data-cleansing SaaS, built at BytePX.
- Multi-sheet workbooks processed in **<2 min at 99.9% accuracy** (15–20× speedup)
- `io.BytesIO` streaming + dynamic type downcasting + `rapidfuzz` (C++ layer) for 10× faster fuzzy matching

`Python` `FastAPI` `PostgreSQL` `Starlette` `RapidFuzz`

</td>
<td width="50%" valign="top">

**🤖 [Birbal 2.0](https://rudrasharma3.github.io/Portfolio/)**
<br/>Multilingual enterprise RAG assistant for UltraTech Cement (Birla White).
- Async NLP pipelines cut query latency by **95%**
- Native Hindi–English context tracking, boosting query efficiency by **60%**

`Python` `FastAPI` `LangChain` `RAG` `NLP`

</td>
</tr>
</table>

<details>
<summary><b>📦 Delivery Date Prediction — 500K+ records</b></summary>
<br/>

E-commerce supply-chain ETA forecasting engine. Tuned an **XGBoost** model across 500K+ historical shipment records with feature-scaling pipelines built around real supply-chain constraints, reducing ETA variance.

`Python` `XGBoost` `Scikit-learn` `Pandas`
</details>

<br/>

## → Experience

```text
BytePX                              Data Engineering Intern       Mar 2026 — Present
UltraTech Cement [Birla White]      AI & ML Intern                Jun 2025 — Jul 2025
SmartBridge                         Generative AI Intern          Jun 2025 — Jul 2025
```

- **BytePX** — Architected DataPurge Studio; built Databricks/Spark automation cutting document-processing time by 90%; trained client Random Forest models with SHAP explainability (50% overhead reduction), deployed on IBM watsonx; mentored 2 junior engineers on Spark & Databricks.
- **UltraTech Cement** — Engineered Birbal 2.0, a bilingual RAG chatbot, cutting response latency 95% and boosting query efficiency 60%.
- **SmartBridge** — Built GenAI architectures with Google Gemini APIs across VAEs, GANs, BERT, and LSTMs.

<br/>

## → Education & Credentials

- **B.Tech, Computer Science (AI/ML)** — UPES Dehradun · CGPA 8.0/10 · 2022–2026
- **Microsoft Certified: Azure AI Engineer Associate** — `957CF25F904A0B46`
- 25+ Google Cloud Skill Badges · 120+ DSA problems on LeetCode · HackerRank Java Gold

<br/>

## → Activity

<div align="center">
<img src="https://github-stats-extended.vercel.app/api?username=RudraSharma3&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" width="49%" alt="GitHub stats" />
<img src="https://streak-stats.demolab.com?user=RudraSharma3&theme=tokyonight&hide_border=true" width="49%" alt="GitHub streak" />
</div>

<br/>

<div align="center">

**[Portfolio](https://rudrasharma3.github.io/Portfolio/)** · **[Client Work](https://freelance-kappa-orpin.vercel.app/)** · **[LinkedIn](https://www.linkedin.com/in/rudra-sharma-3508a227b)** · **[Email](mailto:rudrasharma93511@gmail.com)**

<img src="https://komarev.com/ghpvc/?username=RudraSharma3&color=22D3C7&style=flat-square&label=PROFILE+VIEWS" alt="Profile Views" />

</div>
