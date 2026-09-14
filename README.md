# Rudra Sharma

**AI & Data Engineer**  
*AI Agents · LLM Systems · Data Engineering · Software Architecture*

[Portfolio](https://rudrasharma3.github.io/Portfolio/) &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/rudra-sharma-3508a227b) &nbsp;|&nbsp; [GitHub](https://github.com/RudraSharma3) &nbsp;|&nbsp; [Email](mailto:rudrasharma93511@gmail.com)

---

I build data-intensive systems, retrieval platforms, and agentic workflows designed around clear architectural boundaries and deterministic validation. My work focuses on bridging data engineering foundations—such as distributed processing with Spark and Databricks—with modern AI engineering patterns, including Model Context Protocol (MCP), context persistence, and contract-first multi-agent orchestration.

---

## 🧭 Currently Building & Researching

- **AI-OS (AI Operating System):** An open research and engineering project establishing the Git repository as the durable operational layer for AI agents, replacing transient conversation memory with structured repository contracts.
- **Contract-First Multi-Agent Systems:** Structuring manager/worker agent topologies that enforce interface contracts before code generation.
- **Deterministic AI Workflows:** Designing systems that combine probabilistic LLM generation with deterministic data validation, schema enforcement, and rule-gated knowledge updates.

---

## 🛠️ Core Engineering Domains

### 🤖 AI Engineering & Agentic Systems
- **Agent Orchestration:** Multi-agent coordination patterns, Manager/Worker hierarchies, proportional orchestration.
- **Context & Memory Architecture:** Model Context Protocol (MCP), persistent repository context, canonical instruction layers (`AGENTS.md`).
- **LLM & RAG Systems:** Retrieval-Augmented Generation, context-aware prompt refinement, hallucination mitigation.

### ⚡ Data Engineering & Platforms
- **Distributed Processing:** Apache Spark, PySpark, Databricks.
- **Data Pipelines:** Automated ETL workflows, asynchronous batch processing, multi-sheet enterprise workbook parsing.
- **Validation & Transformation:** Schema enforcement, deterministic data cleansing, structured data extraction.

### 🏗️ Backend & System Architecture
- **API & Service Design:** FastAPI, REST APIs, asynchronous request handling.
- **Data Persistence & Security:** PostgreSQL, Supabase, Row Level Security (RLS), role-based authentication.
- **Software Practices:** Modular design, Architecture Decision Records (ADRs), contract-first development.

### 📊 Applied Machine Learning
- **Predictive Modeling:** Supervised learning, Gradient Boosting, ensemble methods.
- **Feature Engineering:** Domain-specific feature extraction, synthetic dataset generation, genomic risk modeling (Polygenic Risk Scores).

---

## 🚀 Featured Engineering Projects

### 1. AI-OS — AI Operating System
*A repository-native operational layer for AI-assisted software engineering.*

- **Problem:** AI coding assistants rely on ephemeral conversational context. Project architecture, conventions, lessons, and security boundaries become fragmented across different models and chat sessions.
- **Architecture & System Design:**
  - **Canonical Source of Truth:** A centralized `AGENTS.md` holds core project constraints, while thin provider adapters (`CLAUDE.md`, `GEMINI.md`, `CODEX.md`) map instructions across tools without duplication.
  - **Gated Self-Modification:** Agent-proposed preferences and conventions are treated as candidate knowledge, requiring review and validation before promotion into persistent rules.
  - **Context-Aware Prompt Refinement:** Enriches ambiguous developer prompts with existing architecture, edge cases, typing contracts, and testing requirements before execution.
  - **Contract-First Multi-Agent Coordination:** A Manager agent establishes type interfaces, API schemas, and component boundaries before Worker agents implement code in parallel.
  - **Proportional Orchestration:** Scales agent topology dynamically—simple tasks execute as single calls, while complex refactors trigger multi-perspective architectural reviews (Minimalist, Scalability, Security).
- **Core Philosophy:** *"Don't just use AI to write code. Engineer the environment in which AI writes code."*
- **Stack:** `Python` · `Git Architecture` · `MCP` · `Markdown Protocol` · `Agent Workflows`
- **Link:** [Project Repository](https://github.com/RudraSharma3)

---

### 2. Enterprise Data & AI Pipelines — BytePX
*Production data pipelines and document transformation systems.*

- **Resume-to-Presentation Automation Pipeline:**
  - Designed an automated ingestion pipeline processing ~30 documents/day.
  - Reduced per-document processing latency from roughly 30 minutes of manual formatting to under 20 seconds.
  - Integrated distributed data handling and enterprise AI parsing services.
  - **Stack:** `Databricks` · `Apache Spark` · `IBM watsonx` · `Python`
- **Asynchronous Multi-Sheet Workbook Engine:**
  - Engineered an asynchronous data processing pipeline handling multi-sheet enterprise workbooks.
  - Achieved execution runtimes under 2 minutes per workbook with approximately 99.9% processing accuracy across structured data tables.
  - **Stack:** `Python` · `PySpark` · `AsyncIO` · `Databricks`

---

### 3. Vaultic — Financial Command & Intelligence Cockpit
*A deterministic personal finance platform with integrated AI advisory workflows.*

- **Problem:** Personal finance applications often separate deterministic balance tracking from predictive budgeting tools, resulting in inaccurate simulations.
- **System Highlights:**
  - Built on PostgreSQL with Supabase, strictly isolating user data via Row Level Security (RLS).
  - Deterministic balance and interest calculation engine separated from probabilistic AI recommendation layers.
  - Interactive scenario simulator evaluating expenditure impact against defined financial goals.
- **Stack:** `FastAPI` · `PostgreSQL` · `Supabase` · `RLS` · `Next.js` · `TypeScript`
- **Link:** [Project Repository](https://github.com/RudraSharma3)

---

### 4. Job Assistant — Decision-Support Platform
*A privacy-first career decision support and technical role fit platform.*

- **System Highlights:**
  - Secure document storage engine utilizing Supabase RLS and token-based authentication.
  - AI-driven gap analysis comparing resume experience with engineering job descriptions to produce structured preparation recommendations.
  - Focuses on candidate decision support rather than indiscriminate job board auto-application.
- **Stack:** `Next.js` · `TypeScript` · `Tailwind CSS` · `Supabase` · `PostgreSQL`
- **Link:** [Project Repository](https://github.com/RudraSharma3)

---

### 5. Polygenic Risk Score Research Platform
*Machine learning research project for genomic risk profiling and predictive modeling.*

- **System Highlights:**
  - Implemented Gradient Boosting algorithms on synthetic patient genomic datasets.
  - Evaluated polygenic feature weightings to assess susceptibility across multi-factorial traits.
  - Applied feature importance analysis to identify primary genomic variant contributors.
- **Stack:** `Python` · `Scikit-Learn` · `Gradient Boosting` · `Pandas` · `NumPy`

---

## 💡 Engineering Principles

- **Architecture Before Generation:** AI generation quality is bounded by the precision of system contracts, types, and architectural documentation.
- **Constrain the Tool:** System constraints, schema validation, and deterministic fallbacks must guard every probabilistic LLM output.
- **Durable Repository Memory:** Permanent project knowledge belongs in version-controlled repository files, not transient conversational contexts.
- **Proportional Orchestration:** Reserve complex multi-agent topologies for non-trivial architectural problems; simple tasks should remain simple.
- **Measurable Verification:** Validate systems against concrete latency, accuracy, and reproducibility metrics rather than assumed generative capability.

---

## 🧰 Technical Stack

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | Python, TypeScript, Java, SQL, JavaScript |
| **AI & LLM Systems** | LLM Integration, RAG Architectures, AI Agents, MCP (Model Context Protocol), Prompt Refinement |
| **Data Engineering** | Apache Spark, PySpark, Databricks, Data Pipelines, ETL Workflows |
| **Backend & Storage** | FastAPI, PostgreSQL, Supabase, Row Level Security (RLS), REST APIs |
| **Web & Interfaces** | Next.js, React, Tailwind CSS |
| **Infrastructure & Tools** | Git, GitHub, Docker, Vercel, Architecture Decision Records (ADRs) |

---

## 💼 Experience

### **Data Engineering Intern** — BytePX
- Developed an automated resume-to-PPT pipeline using Databricks, Apache Spark, and IBM watsonx, cutting document processing time from ~30 minutes to <20 seconds for ~30 documents/day.
- Built an asynchronous workbook processing pipeline capable of handling complex multi-sheet enterprise datasets in <2 minutes with ~99.9% data accuracy.

---

## 🎓 Education

**B.Tech in Computer Science (Artificial Intelligence & Machine Learning)**  
*UPES, Dehradun*

---

## 📜 Certifications & Selected Recognitions

- **HackerRank:** Java (Basic) Certified & Java Golden Badge
- **Job Simulations:** Accenture Software Engineering & Accenture Consulting Simulations
- **UDYAM'2023:** 1st Runner-Up — Business Case Competition
- **Community:** Vedanta Foundation Nand Ghar Social Internship

---

## 📬 Contact & Collaboration

I am open to discussions regarding **AI Engineering**, **Agentic Systems**, **Data Platforms**, and **Backend Architecture**.

- **LinkedIn:** [linkedin.com/in/rudra-sharma-3508a227b](https://www.linkedin.com/in/rudra-sharma-3508a227b)
- **Portfolio:** [rudrasharma3.github.io/Portfolio](https://rudrasharma3.github.io/Portfolio/)
- **Email:** [rudrasharma93511@gmail.com](mailto:rudrasharma93511@gmail.com)
