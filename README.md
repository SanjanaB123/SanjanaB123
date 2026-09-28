# Hey, I'm Sanjana 👋

AI/ML engineer focused on LLM inference, agentic systems, and MLOps infrastructure that ships.

MS Data Science @ Northeastern · Graduating Dec 2026 · Boston, MA

---

## Recent focus: LLM inference internals

- **vLLM benchmarking on Apple Silicon** — Measured continuous batching, prefix caching (5.3x faster TTFT), and the compute-vs-memory bottleneck on an M3, with a controlled A/B and log-level evidence. → [repo](https://github.com/SanjanaB123/vllm-metal-benchmarks)
- **[Merged] vLLM (vllm-metal)** — Gemma 4 bf16 split-KV decode parity test coverage, head size 512 → [PR #855](https://github.com/vllm-project/vllm-metal/pull/855)
- **[Merged] llama-cpp-python** — Enabled unified KV cache to preserve per-sequence context in batch embeddings → [PR #2217](https://github.com/abetlen/llama-cpp-python/pull/2217)
- **[Merged] openllmetry** — Fixed `GenAICustomOperationName` semconv version bump → [PR #3826](https://github.com/traceloop/openllmetry/pull/3826)

---

## Selected projects

- **Multi-Agent AutoML** — LangGraph system (classification, regression, clustering, feature-engineering subgraphs) with supervisor/planner/memory agents and MCP-exposed tooling. Cut project turnaround from ~1 week to ~3 hours; used by real clients.
- **RAG Pipeline on GCP** — Gemini + Pinecone hybrid retrieval, 71% → 86% answer relevance (RAGAS), deployed on Cloud Run at 500+ daily queries.
- **MLOps Demand Forecasting** — XGBoost + Prophet, Optuna tuning, Airflow orchestration, DVC/GCS versioning, auto-rollback on regression. Demoed at Google Cambridge.

---

## Experience

- **ML & GenAI Intern** — Seagate Technology *(agentic pipelines, RAG, backend infra)*
- **ML Intern** — Transformly AI *(LangGraph multi-agent AutoML, MCP)*
- **ML Intern** — Fuzzy Cloud *(RAG on GCP, Vertex AI, Gemini)*

---

## Stack

**LLM & inference:** vLLM, llama.cpp, LangGraph, LangChain, MCP, Pinecone, Hugging Face
**ML & MLOps:** PyTorch, XGBoost, MLflow, Optuna, Airflow, DVC
**Deployment:** FastAPI, Docker, Cloud Run, GCS, GitHub Actions
**Languages:** Python, SQL, C++, Go

📫 sanjanab0804@gmail.com
