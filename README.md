# Youssef Chaouki

AI engineer in Montréal. I build LLM systems that are measured before they ship: retrieval, agents, fine-tuning and the evaluation harness around them.

- M.A.Sc. Computer Engineering at Polytechnique Montréal (AI and cybersecurity), double degree with INSA Lyon
- Co-founder of [Erudi](https://www.erudi.app), custom and local AI for small and mid-sized businesses
- Finalist, Mila AI Safety Hackathon (March 2026)

## Selected work

| Project | What it is | Evidence |
|---|---|---|
| [finsage-lite](https://github.com/YoussefChaouki/finsage-lite) | Search and Q&A over SEC 10-K filings: BM25 + dense vectors + rank fusion written from scratch, local LLM, React front end | Recall@5 from 72 % to 87 % across four benchmarked configurations on a FinanceBench subset; 291 unit tests in CI |
| [Nexus](https://github.com/YoussefChaouki/Nexus) | Multi-agent threat intelligence for AI systems: five LangGraph agents with a Critic feedback loop, evidence fetched through custom MCP servers (arXiv, NVD) | 80 % threat-surface coverage vs 27 % for a single prompt on a 5-target benchmark; 92 % test coverage in CI |
| [dayone-codeml](https://github.com/YoussefChaouki/dayone-codeml) | Offline-first WhatsApp agent that turns photos of a paper maternal registry into a verified digital record, with local AI only | 93.4 % field accuracy on held-out patients, pre-registered protocol, known limits reported |
| [erudi](https://github.com/erudi-app/erudi) | Open-source desktop app that runs open models on your own machine (MLX, llama.cpp), chat with your documents, fully offline | Shipped for macOS, Windows and Linux |
| [citadel-rag](https://github.com/YoussefChaouki/citadel-rag) | Self-hosted RAG service on FastAPI, pgvector and Ollama; no data leaves the host | Evaluation harness with a golden dataset; CI with integration tests |
| [equialgo-fairness-audit](https://github.com/YoussefChaouki/equialgo-fairness-audit) | Bias audit and correction of a scholarship-allocation model (hackathon, team project) | 94.6 % accuracy against true merit, pre-registered decision rule, per-cycle fairness monitoring |

## Stack

Python, PyTorch, Hugging Face, LangGraph, FastAPI, PostgreSQL / pgvector, Redis, Docker, GitHub Actions. Also C/C++, Java and SQL.

## Contact

[LinkedIn](https://www.linkedin.com/in/youssef-chaouki/) · [erudi.app](https://www.erudi.app)
