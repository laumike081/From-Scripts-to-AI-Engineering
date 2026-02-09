# From Scripts to Systems: The Computational Biologist → AI Engineer Roadmap

**Author:** [laumike081](https://github.com/laumike081)  
**Background:** Ph.D. Computational Biologist  
**Goal:** Senior AI/ML Engineer (Focus: Agents, Cloud, Scaling)  
**Timeline:** 6 Months  

---

## 🧬 The Why: "Biology is becoming an Engineering Discipline."

I spent years writing Python scripts to analyze biological data. But the future of biology isn't just *analyzing* data—it's **building systems** that can reason, scale, and discover.

This repository documents my transition from "running scripts in a notebook" to **building production-grade AI systems**.

---

## 🗺️ The Roadmap: The 3 Pillars of AI Engineering

To bridge the gap from "Scientist" to "Engineer," I am focusing on three core pillars:

### ☁️ Pillar 1: Cloud & Infrastructure (The Foundation)
*Stop running on localhost. Start shipping.*
- **Goal:** deploy scalable, fault-tolerant systems on AWS/GCP.
- **Key Tech:** Docker, Kubernetes (K8s), Terraform, CI/CD (GitHub Actions).
- **Project:** Deployed **BioAgent** API on AWS ECS with auto-scaling.

### 🤖 Pillar 2: LLMs & Agentic AI (The Brain)
*Stop fine-tuning. Start orchestrating.*
- **Goal:** Build autonomous agents that can plan, use tools, and reason over scientific data.
- **Key Tech:** LangChain, LangGraph, Smolagents, RAG (Vector DBs).
- **Project:** **BioAgent** (Multi-agent researcher) & **DrugRAG** (Knowledge graph for drug discovery).

### 📈 Pillar 3: Scaling & Data Engineering (The Muscle)
*Stop using Pandas CSVs. Start using Spark.*
- **Goal:** Process massive biological datasets (Genomics/Cheminformatics) efficiently.
- **Key Tech:** Databricks (PySpark), Delta Lake, Nextflow, Snowflake.
- **Project:** **MolGen** pipeline processing 2M+ compounds on Databricks.

---

## 📅 The Daily Grind (Routine)

| Time | Activity | Focus |
| :--- | :--- | :--- |
| **05:00 - 08:00** | 🧠 Deep Work | Learning New Tech (Papers/Courses) |
| **10:30 - 12:00** | ⚔️ The Gauntlet | LeetCode Hard + System Design |
| **13:30 - 15:30** | 🛠️ Project Build | Coding & Deploying Portfolio Apps |

---

## 🚀 Projects (Proof of Work)

| Project | Description | Stack | Status |
| :--- | :--- | :--- | :--- |
| **[BioAgent](./BioAgent)** | Autonomous Gene Research Agent | LangGraph, FastAPI, Docker | 🚧 Building |
| **[DrugRAG](./DrugRAG)** | RAG for Drug Discovery Papers | ChromaDB, Groq, Streamlit | 🚧 Building |
| **[MolGen](./MolGen)** | Generative AI for Molecules | PyTorch, RDKit, Databricks | 📅 Planned |

---

*This is a living document. I update it daily with what I learn, what I build, and where I fail.*
