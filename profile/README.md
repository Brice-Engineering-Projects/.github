# 🏗️ Brice Engineering Systems

> A suite of engineering and municipal intelligence tools — combining Python, data automation, and applied infrastructure analytics to modernize the civil engineering workflow.

---

## 🧭 Overview

**Brice-Engineering-Systems** brings together applications that bridge traditional civil engineering with data-driven software.  
Each project is designed to streamline municipal processes, automate repetitive engineering tasks, and introduce scalable backend intelligence into public-sector infrastructure work.

Where the **Backend Projects** org focuses on pure software engineering,  
this org focuses on **practical engineering applications** — built by an engineer, for engineers.

---

## ⚙️ Core Stack

| Category | Tools / Frameworks |
|-----------|-------------------|
| **Languages** | Python 3.12+ |
| **Frameworks** | Flask • FastAPI • Jinja2 |
| **Database** | PostgreSQL • SQLite • DuckDB |
| **Data & APIs** | Pandas • Requests • OpenAI / Whisper (for local AI) |
| **Automation & Docs** | Word / Docx • Markdown • Pandoc |
| **DevOps** | uv • GitHub Actions • Docker (select projects) |

---

## 🚀 Featured Repositories

| Repo | Description | Status |
|------|--------------|--------|
| **[Cost-Query-Pro](https://github.com/Brice-Engineering-Systems/Cost-Query-Pro)** | A Python-powered app to search, manage, and analyze unit cost data from infrastructure projects — streamlining cost lookups, data uploads, and historical bid tracking. | 🧮 Active Development |
| **[Projex](https://github.com/Brice-Engineering-Systems/Projex)** | Project planning and checklist system for civil and municipal project workflows. Built to track tasks, sequences, and construction readiness. | 🗂️ Private |
| **[Fund-Finder](https://github.com/Brice-Engineering-Systems/Fund-Finder)** | API-driven application to locate infrastructure and grant funding opportunities for municipalities. Includes dataset lookups and funding criteria matching. | 💰 In Progress |
| **[Minute-Gen](https://github.com/Brice-Engineering-Systems/Minute-Gen)** | Local meeting-minute generator that converts audio recordings into formatted Word documents — no external servers or cloud dependencies required. | 🗣️ Public Utility |

---

## 🧩 Engineering Focus

Each project solves a tangible civil engineering problem:

| Goal | Example Application |
|------|---------------------|
| **Data-driven design** | Cost Query Pro’s bid-tab analytics and cost indexing |
| **Automation of admin tasks** | Minute-Gen’s transcript → Word pipeline |
| **Funding and resource intelligence** | Fund-Finder’s API integrations for municipal programs |
| **Project coordination** | Projex’s construction phase task tracking |

---

## 🧰 Development Philosophy

1. **Real problems, real datasets** — Each project reflects actual engineering pain points.  
2. **Full autonomy** — Designed to run locally or deploy easily on municipal infrastructure.  
3. **Minimal AI reliance** — AI is used for summarization or transcription only when strictly needed.  
4. **Transparency & reproducibility** — All calculations, datasets, and reports are open and verifiable.  

---

## 🧱 Example Architecture (Cost-Query-Pro)

```plaintext
src/
  ├── api/            # REST endpoints for project & cost data
  ├── models/         # Database schema for bid items, units, history
  ├── services/       # Query engine & analytics functions
  ├── utils/          # Helper methods, validation, I/O
  └── templates/      # Jinja2-based front-end
tests/
docs/
.env.example
README.md
```

---

## 🧪 Current Focus

- 🔍 Expanding **Cost Query Pro** with region-based filtering and trend dashboards.  
- 🧱 Integrating **Projex** into a modular civil project planning system.  
- 💡 Adding **offline inference** options for **Minute-Gen**.  
- 💰 Linking **Fund-Finder** datasets to state and federal API endpoints.  

---

## 🧠 AI Usage Disclosure

Setup files (e.g., `.gitignore`, `README.md`, CI templates) may be generated with AI assistance for speed and consistency.  
However, **engineering logic, analysis modules, and workflow design are fully human-built**, grounded in actual civil-engineering practice.

> AI = scaffolding.  
> Human = engineering systems.

---

## 🧾 License

MIT License © 2025 Brice Nelson  
Open for public learning and collaboration where applicable.

---

## 🌐 Connect

- 🌐 **Portfolio:** [https://www.devbybrice.com](https://www.devbybrice.com)  
- 🧠 **Blog:** [Medium — Data, Infrastructure & Automation](https://medium.com/@bricenelson)  
- 💼 **LinkedIn:** [Brice Nelson](https://www.linkedin.com/in/brice-nelson)

---

> *“Where data meets design — building smarter infrastructure through code.”*
