# From Scripts to Systems: The Computational Biologist → AI Engineer Roadmap

---

## 🧬 The Why: "Biology is becoming an Engineering Discipline."

I spent years writing Python scripts to analyze biological data. But the future of biology isn't just *analyzing* data—it's **building systems** that can reason, scale, and discover.

This repository documents my transition from "running scripts in a notebook" to **building production-grade AI systems**.

### My "Why"
1.  **The Shift:** Biology used to be about *analyzing* data. The future is about *generating* it (AlphaFold, Diffusion Models). I want to build the generators, not just use the output.
2.  **The Scale:** Academic scripts don't scale. To cure diseases, we need industrial-grade systems that run on thousands of GPUs, not a single laptop.
3.  **The Agentic Future:** LLMs aren't just chatbots; they are reasoning engines. I believe **AI Agents** will be the ones designing the next blockbuster drugs. I want to be the one architecting them.

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

## 📝 The Protocol: How I Test Myself (The Gauntlet)

I don't just "watch tutorials." I test myself daily with rigorous engineering standards.

### 1. The Algorithm Gauntlet (LeetCode)
- **Goal:** 25 Problems/Day (Medium/Hard).
- **Focus:** Arrays, HashMaps, Trees, Graphs, DP.
- **Why:** To prove I can write optimized, bug-free code under pressure.

### 2. The SQL & Data Gauntlet (StrataScratch)
- **Goal:** Master complex SQL queries & data transformations.
- **Focus:** Window functions, complex joins, data cleaning.
- **Why:** Data is the fuel. If I can't query it efficiently, I can't build AI on top of it.

### 3. The System Design Gauntlet (Mock Interviews)
- **Goal:** Design scalable ML systems from scratch (e.g., "Design a Drug Discovery Platform").
- **Focus:** Trade-offs (Latency vs. Throughput), Data Pipelines, Serving Infrastructure.
- **Why:** Senior Engineers are hired for their design decisions, not just their code.

---

## 📚 The Curriculum (GitHub Resources)

### 🗺️ The Roadmap (Skill Trees)
- **[roadmap.sh/ai-engineer](https://roadmap.sh/ai-engineer)** - The definitive skill tree.
- **[donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer)** - Scalable system architecture.

### 🤖 The Agentic & LLM Track
- **[karpathy/minGPT](https://github.com/karpathy/minGPT)** - Build GPT from scratch in 300 lines of PyTorch. (Must do).
- **[facebookresearch/llama](https://github.com/facebookresearch/llama)** - Production-grade LLM inference code.
- **[huggingface/course](https://github.com/huggingface/course)** - Transformers & NLP from scratch.

### 👁️ The Vision & Bio Track
- **[open-mmlab/mmdetection](https://github.com/open-mmlab/mmdetection)** - Gold standard for Object Detection (Cells/Tissues).
- **[dair-ai/ML-YouTube-Courses](https://github.com/dair-ai/ML-YouTube-Courses)** - CS224N (NLP) & CS231n (Vision).

### 🏭 The Production Track (Real World ML)
- **[eugeneyan/applied-ml](https://github.com/eugeneyan/applied-ml)** - Engineering blogs from Netflix, Uber, Spotify.
- **[chiphuyen/ml-interviews-book](https://github.com/chiphuyen/ml-interviews-book)** - System Design for ML Engineers.

---

## 📅 The Daily Grind (Routine)

| Time | Activity | Focus |
| :--- | :--- | :--- |
| **05:00 - 08:00** | 🧠 Deep Work | Learning New Tech (Papers/Courses) |
| **10:30 - 12:00** | ⚔️ The Gauntlet | LeetCode + StrataScratch |
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
