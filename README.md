<h1 align="center">Hi, I'm Vansh Kamra 👋</h1>
<h3 align="center">CS @ BITS Pilani | Building scalable backend systems, API infrastructure, and AI tooling.</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/vanshkamra12" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:vanshkamra27@email.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://vanshkamra12.github.io" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-252525?style=for-the-badge&logo=mac&logoColor=white" alt="Portfolio" />
  </a>
</p>

---

### 👨‍💻 About Me

I'm a backend and AI infrastructure engineer who cares about systems that are observable, correct under load, and maintainable. Instead of just wrapping LLM APIs, I focus on the infrastructure layer—routing, rate limiting, stateful agent memory, and model fine-tuning.

- 🎓 **Education:** BSc Computer Science @ BITS Pilani (2024-2027)
- 🔭 **Currently Building:** **InferGate**, a 5-microservice AI API gateway with distributed tracing and Redis rate limiting.
- 🤝 **Open Source:** Active contributor to **Meshery (CNCF)** and **vscode-swift**.
- 💬 **Ask me about:** Microservices architecture, LangGraph state machines, QLoRA fine-tuning, and Docker networking.

---

### 🏗️ Featured Engineering Work

| Project | Description | Tech Stack |
|---------|-------------|------------|
| **[InferGate-API-Gateway](https://github.com/vanshkamra12/InferGate-API-Gateway)** | **Production-grade AI Request Router.** Orchestrates 5 microservices via Docker Compose. Implements Redis sliding-window rate limiting (5 req/60s), MongoDB `$expr` quota guards to prevent race conditions, and distributed tracing via `x-request-id`. | `TypeScript`, `Express`, `Redis`, `MongoDB`, `Docker` |
| **[ServiceHive-Agentic-Workflow](https://github.com/vanshkamra12/ServiceHive-Agentic-Workflow)** | **Stateful SaaS Support Agent.** Multi-node LangGraph state machine with persistent memory across conversation turns, intent classification, and FAISS-based RAG. Exposed via FastAPI webhooks. | `Python`, `LangGraph`, `FastAPI`, `FAISS` |
| **[Codebase-Analyzer-CLI](https://github.com/vanshkamra12/codebase-analyzer-cli)** | **Static Analysis Engine.** CLI tool for large Python codebases. Extracted 31k+ functions and 182k edges from Django's source code to compute McCabe complexity and export rich terminal/markdown reports. | `Python`, `ast` |
| **[CyberThreat-Intel-LLM](https://github.com/vanshkamra12/CyberThreat-Intel-LLM)** | **Specialized SecOps Model.** Fine-tuned Phi-3-mini (3.8B params) using QLoRA on a T4 GPU. Generates structured MITRE ATT&CK mappings and YARA rules from raw CVE data. | `PyTorch`, `Transformers`, `QLoRA` |

---

### 🛠️ Core Technologies

**Languages:** Python, TypeScript, C++, SQL <br>
**Backend & Systems:** Node.js/Express, FastAPI, Redis, PostgreSQL, MongoDB <br>
**AI/ML:** LangGraph, PyTorch, HuggingFace, FAISS <br>
**Infrastructure:** Docker, Docker Compose, Nginx, Linux, GitHub Actions <br>

---

<p align="center">
  <i>"Ship real. Break things openly, and build systems that scale."</i>
</p>
