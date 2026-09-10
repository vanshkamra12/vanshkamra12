<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Space+Mono&weight=500&size=22&pause=1000&color=FFFFFF&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Vansh+Kamra;AI+%26+Backend+Engineer;Architecting+AI+Infrastructure" alt="Typing SVG" />
</div>

<p align="center">
  <a href="https://www.linkedin.com/in/vanshkamra12" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:vanshkamra27@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://vanshkamra.me" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-252525?style=for-the-badge&logo=mac&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://huggingface.co/vanshkamra12" target="_blank">
    <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  </a>
</p>

---

### ⚙️ System Specifications

| Component | Specification |
|:---|:---|
| **Core Architecture** | Backend Systems & Applied AI |
| **Execution Engine** | Scaler School of Technology |
| **Primary Protocols** | Python, TypeScript, Node.js, C++ |
| **Current Focus** | Building the infrastructure layer (API Gateways, Rate Limiters, Stateful Checkpointers) instead of just LLM wrappers. |
| **Key Subsystems** | `Docker` `LangGraph` `Redis` `MongoDB` `PyTorch` `FastAPI` |
| **Recent Signal** | 🥇 1st place — Synapse, Ascent Builders TechFest (Scaler School of Technology), May 2026 |

---

### 🏗️ Featured Engineering Work

| Project | Description | Tech Stack |
|---------|-------------|------------|
| **[CyberThreat-Intel-LLM](https://github.com/vanshkamra12/CyberThreat-Intel-LLM)** · [🤗 Live Demo](https://huggingface.co/spaces/vanshkamra12/CyberThreat-Intel-Analyzer) | **Specialized SecOps Model.** Fine-tuned Phi-3-mini (3.8B) with QLoRA 4-bit + Unsloth on a single T4 — 29.8M trainable params (0.78%), loss 0.83 → 0.34 in ~20 min. Turns raw CVE data into MITRE ATT&CK mappings with YARA and Sigma detection rules. Model and demo published on Hugging Face. | `PyTorch`, `Transformers`, `QLoRA`, `Unsloth` |
| **[FraudShield-MLOps](https://github.com/vanshkamra12/fraudshield-mlops)** | **Real-time Fraud Detection Pipeline.** End-to-end MLOps system processing streaming transactions via Kafka. LightGBM scoring service at <10ms p95, trained on a strict temporal split (ROC-AUC 0.907, PR-AUC 0.516 — no lookahead leakage). Weekly Airflow retraining, Evidently drift detection, Prometheus/Grafana monitoring across 10 services. | `Kafka`, `FastAPI`, `MLflow`, `Airflow`, `Docker` |
| **[InferGate-API-Gateway](https://github.com/vanshkamra12/InferGate-API-Gateway)** | **Production-grade AI Request Router.** Orchestrates 5 microservices via Docker Compose. Implements Redis sliding-window rate limiting (5 req/60s), MongoDB `$expr` quota guards to prevent race conditions, and distributed tracing via `x-request-id`. | `TypeScript`, `Express`, `Redis`, `MongoDB`, `Docker` |
| **[GradeSense](https://github.com/vanshkamra12/gradesense)** | **Evidence-Grounded Answer Grading.** Grades student answer scripts against a marking scheme and annotates the exact region of the page where the supporting evidence sits — every score traceable back to its source rather than an opaque number. | `TypeScript` |
| **[DataWarehouseOps-Env](https://github.com/vanshkamra12/DataWarehouseOps-Env)** | **RL Environment for Data-Engineering Agents.** OpenAI Gym-compatible environment over SQLite with stateless HTTP design, per-reset session isolation, and sandboxed destructive queries. Three task tiers (data cleaning, PII masking, query optimization) with shaped reward functions. | `Python`, `Gym`, `SQLite`, `Docker` |
| **[Codebase-Analyzer-CLI](https://github.com/vanshkamra12/codebase-analyzer-cli)** | **Static Analysis Engine.** CLI tool for large Python codebases. Extracted 31k+ functions and 182k call-graph edges from Django's source to compute McCabe complexity and export rich terminal/markdown reports. | `Python`, `ast` |

---

### 🛠️ Core Technologies

**Languages:** Python, TypeScript, C++, SQL <br>
**AI/ML:** QLoRA fine-tuning, LangGraph, RAG (FAISS, ChromaDB), PyTorch, HuggingFace, LightGBM <br>
**MLOps:** MLflow, Airflow, Kafka, Evidently, model serving, evaluation pipelines <br>
**Backend & Systems:** Node.js/Express, FastAPI, Redis, PostgreSQL, MongoDB <br>
**Infrastructure:** Docker, Docker Compose, Nginx, Linux, GitHub Actions <br>

---

<p align="center">
  <i>"Ship real. Break things openly, and build systems that scale."</i>
</p>
