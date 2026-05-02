# Mahender Rao Samperboyina

Software Engineer (AI/ML) building agentic AI platforms in production. 6+ years across software engineering, ML research, and enterprise automation. Currently at Bayesics, where I architect a reusable multi-agent framework powering internal AI applications for NASA program teams and federal R&D partners. MS Computer Science from Rowan University (4.0 GPA).

## What I'm working on

- **Agentic AI platforms.** Multi-agent orchestration with LangGraph, sandboxed tool execution, LLM-as-judge evaluation pipelines, prompt-injection defenses, and context-engineering primitives for production deployment.
- **Open-source MCP servers.** Domain-specific Model Context Protocol servers that connect AI assistants to real-world data and tools. Three so far - legal research, construction trades, and HR compliance.
- **LLM safety and evaluation.** Fine-tuning, machine unlearning, grounding judges, and golden-dataset regression as part of any AI shipping discipline.

## Featured work

| Repo | What it is |
|---|---|
| [legal-mcp](https://github.com/Mahender22/legal-mcp) | Comprehensive US legal MCP server. 18 tools spanning case law (4M+ court opinions via CourtListener), practice management (Clio), and federal filings (PACER). MIT licensed. |
| [trades-mcp](https://github.com/Mahender22/trades-mcp) | First MCP server for construction trades. 13 tools for contractor license verification across CA/TX/FL/NY, BLS labor rates, material pricing, project cost estimation. 68+ passing tests. MIT licensed. |
| [Machine-Unlearning-SLM](https://github.com/Mahender22/Machine-Unlearning-SLM) | Fine-tuned Llama 3.2 3B on 12K+ synthetic records to filter 500+ protected entities. Multi-GPU inference on dual NVIDIA P40s, 2.3s -> 1.1s latency on 10K query evaluations. |
| [GNN-for-forecasting-coordinated-moving-objects](https://github.com/Mahender22/GNN-for-forecasting-coordinated-moving-objects) | Spatio-temporal GCN-LSTM models for multi-agent trajectory forecasting. 22-node temporal graphs, 300K+ frames. From my MS research at Rowan. |

## Tech stack

**AI / agents.** LangGraph, AutoGen, MCP (Model Context Protocol), Anthropic Claude, OpenAI GPT, Ollama, LangChain, Hugging Face (Transformers, PEFT), pgvector, FAISS, RAG, LLM-as-judge.

**Backend.** Python 3.11 (asyncio), FastAPI, SQLAlchemy 2.0, PostgreSQL, Redis, Celery, Pydantic v2.

**Cloud and infra.** AWS (EKS, RDS, Lambda, S3, Bedrock, SageMaker), Azure (AKS, AI Foundry), Docker, Kubernetes, Terraform, GitHub Actions.

**Practices.** TDD, hexagonal architecture, evaluation-driven shipping, OWASP LLM Top 10 + NIST AI RMF security baselines.

## Contact

- Email: mahendersam5640@gmail.com
- LinkedIn: [linkedin.com/in/mahender-samperboyina-43a865142](https://www.linkedin.com/in/mahender-samperboyina-43a865142)
- Currently open to: Software Engineer / AI Engineer roles, US-based, hybrid or remote

## Acknowledgments

Some of my domain-specific MCPs draw from public datasets and APIs (CourtListener, PACER, Clio, CSLB, BLS, NYC Open Data, Texas open data, MyFloridaLicense). Thanks to those teams for keeping the data accessible.
