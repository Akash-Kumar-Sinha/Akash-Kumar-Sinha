# Akash Kumar Sinha

**Systems & Backend Engineer**

Building scalable backend services, distributed systems, and low-level tooling in Go and Rust — driven by curiosity to understand what happens under the hood, and exploring AI/ML from first principles in my free time.

[Portfolio](https://akashkrsinha.com) · [Writing](https://akashkrsinha.com/writing) · [DSA](https://akashkrsinha.com/problem-solving) · [Schedule a Call](https://cal.com/akash-krsinha/15min) · [Email](mailto:aks.krsinha@gmail.com)

---

## About

I am a systems and backend engineer focused on how platforms work under the hood. Rather than treating frameworks or databases as black boxes, I care about the storage engines, concurrency models, race conditions, memory layouts, and architectural trade-offs that dictate production reliability and scale.

In my free time, I channel that same curiosity into exploring AI/ML from the ground up. Instead of just calling high-level model APIs, I like to understand the mechanics from first principles: writing autograd engines with dynamic DAGs, experimenting with transformer inference loops, and building vector search systems.

> *Approach: Start with the problem, not just the ticket. Learn. Build. Break. Understand. Build better.*

---

## Open Source Contributions

- **[OpenTelemetry Collector Contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib)** (`Go`) — [PR #46947](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/46947)  
  Resolved critical nil-pointer dereferences during collector shutdown by eliminating race conditions across file export routines, hardening export handlers against closed-pipe errors, and orchestrating clean background flusher goroutine lifecycles.

- **[Entros Protocol Executor Node](https://github.com/entros-protocol/executor-node)** (`Rust`) — [PR #12](https://github.com/entros-protocol/executor-node/pull/12)  
  Engineered a lock-free status and metrics layer using `AtomicU64` for high-throughput Axum handlers, implemented constant-time credential verification (`subtle::ConstantTimeEq`) against timing attacks, and introduced TTL-based balance caching.

---

## Projects

| Project | Description | Stack |
| :--- | :--- | :--- |
| **[Aks IDE](https://github.com/Akash-Kumar-Sinha/Aks_ide)** | Cloud development environment delivering low-latency terminal interaction and execution inside isolated Docker containers via WebSockets and Monaco. | Rust, Docker, WebSockets, Monaco |
| **[Akssora Search](https://github.com/Akash-Kumar-Sinha/Akssora-search)** | Multimodal media search engine for searching inside videos using visual embeddings and transcripts (*"grep for media"*). | Python, Embeddings, Vector Search |
| **[Autograd Engine](https://github.com/Akash-Kumar-Sinha/autograd)** | Scalar-valued automatic differentiation engine built from scratch with dynamic DAG computation graphs, reverse-mode autodiff via topological sort, and neural network primitives (MLP). | Python, Autodiff, DAG, Deep Learning |
| **[Candle GPT](https://github.com/Akash-Kumar-Sinha/candle-gpt)** | Lightweight inference engine for GPT-2 models optimized for resource-efficient transformer execution and parallel processing. | Rust, Transformers, Inference Engine |

---

## Technical Writing

In-depth technical writeups on distributed systems, backend internals, and machine learning at [akashkrsinha.com/writing](https://akashkrsinha.com/writing):

- **[Consistent Hashing: Distributing Data Across Servers the Smart Way](https://akashkrsinha.com/writing/consistent-hashing)**  
  Solving modulo resharding cascades and balancing load with virtual nodes.

- **[Designing a Distributed Unique ID Generator](https://akashkrsinha.com/writing/design-a-unique-id-generator-in-distributed-system)**  
  Snowflake bit allocations, clock drift failure modes, and modern UUIDv7 / ULID architectures.

- **[Stale-While-Revalidate: Caching Without Latency Spikes](https://akashkrsinha.com/writing/stale-while-revalidation)**  
  Taming thundering herds and cache stampedes with distributed locks and probabilistic early expiration.

- **[Design a Rate Limiter](https://akashkrsinha.com/writing/rate-limiter)**  
  Algorithms, edge mitigation, and distributed state coordination.

---

## Core Competencies

- **Languages:** Go, Rust, Python, TypeScript, SQL, C++
- **Distributed Systems & Storage:** Redis, PostgreSQL, B+ Trees, Kafka, WebSockets, Microservices, Lock-free Concurrency
- **Infrastructure & Reliability:** Docker, Kubernetes, Linux Internals, Terraform, CI/CD, Prometheus Metrics
- **Web & Frameworks:** Axum, Gin, React, Next.js, Tailwind CSS
- **Curiosity & Free Time (AI/ML):** Dynamic DAGs, Reverse-mode Autodiff, Transformer Inference, Embeddings, PyTorch, Computer Vision, DDPM

---

## Contact

- **Website:** [akashkrsinha.com](https://akashkrsinha.com)
- **Writing:** [akashkrsinha.com/writing](https://akashkrsinha.com/writing)
- **Schedule a Call:** [cal.com/akash-krsinha/15min](https://cal.com/akash-krsinha/15min)
- **Email:** [aks.krsinha@gmail.com](mailto:aks.krsinha@gmail.com)
- **DSA & Problem Solving:** [akashkrsinha.com/problem-solving](https://akashkrsinha.com/problem-solving)
