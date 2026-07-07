# Hi there! I'm Kriti Bhardwaj 👋

Systems Software Engineer focused on high-performance LLM optimization, serving engine architectures, and distributed systems. 

---

## 🛠️ Specialized Technical Focus

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **LLM Inference Optimization** | PyTorch, Hugging Face, KV Cache Management, Speculative Tree Verification, PagedAttention Concepts |
| **Distributed Systems & Infra** | Python (FastAPI, Asyncio), Go, Docker, Nginx (Reverse Proxy & Rate Limiting), Prometheus Metrics |
| **Storage & Caching** | PostgreSQL (DBaaS, pg_stat_statements), Redis, custom Trie/Radix structures |
| **Developer Tools** | Git, Shell scripting, WebSocket streaming, Server-Sent Events (SSE) |

---

## 🚀 Flagship Projects

### 1. [vLLM-Style Inference Serving Engine](https://github.com/kriti768/systems-portfolio)
An optimized serving layer built from scratch to maximize throughput and minimize latency for concurrent LLM generation workloads.
* **Continuous Batching Scheduler**: Iteration-level scheduling incorporating chunked prefill tasks and LIFO-preemption heuristics.
* **Radix Cache Manager**: Shared prefix block caching with LRU leaf eviction, reducing duplicate prompt computations.
* **Tree-based Speculative Verification**: Width-2, depth-2 draft model candidate tree verified in a single query forward pass using a custom 7-token tree-attention mask.
* **Telemetry Control Center**: Modern dashboard UI monitoring physical cache grids, radix structures, and stream performance in real-time.

### 2. [PgExplorer Database Analyzer](https://github.com/kriti768/db-explorer)
A remote visual database management utility for testing connection bottlenecks, executing SQL sandboxes, and analyzing PostgreSQL stats tables.
* Highly responsive developer dashboard built to safely test DBaaS integrations.
* Secure remote SSL handshake capabilities for external production hosting nodes.

---

## 📊 GitHub Metrics & Contributions

<div align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=kriti768&show_icons=true&theme=nord&count_private=true" alt="Kriti's GitHub Stats" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kriti768&layout=compact&theme=nord" alt="Top Languages" height="150" />
</div>

---

## 📫 How to Reach Me
* **Email**: [kritibhardwaj1920@gmail.com](mailto:kritibhardwaj1920@gmail.com)
* **GitHub**: [@kriti768](https://github.com/kriti768)
* **Goal**: Seeking Infrastructure, Systems, or AI-Platform engineering roles where I can build clean, optimized compilers, kernels, or serving engines.
