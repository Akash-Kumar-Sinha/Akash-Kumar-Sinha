# Akash Kumar Sinha

**AI/ML · Backend Systems · Distributed Architecture**

Designing and building resilient backend systems and AI/ML architectures &dash from high-scale distributed services and storage engines to neural networks and inference pipelines built from first principles.

[Portfolio](https://akashkrsinha.com) · [Writing](https://akashkrsinha.com/writing) · [Schedule a Call](https://cal.com/akash-krsinha/15min) · [Email](mailto:aks.krsinha@gmail.com) · [LeetCode](https://leetcode.com/u/akash_krsinha/)

---

## About

Building software is less about simply writing code and more about understanding problems deeply enough to build the right thing.

Rather than treating frameworks or models as black boxes, I focus on what makes them work under the hood &dash the storage engines and concurrency models powering distributed backends, the mathematical foundations of gradient descent and transformers, and the engineering trade-offs that shape production scalability.

> _Approach: Start with the problem, not just the ticket. Learn. Build. Break. Understand. Build better._

---

## Open Source Contributions

- **[OpenTelemetry Collector Contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib)** (`Go`) &dash [PR #46947](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/46947)  
  Resolved critical nil-pointer dereferences during collector shutdown by eliminating race conditions across file export routines, hardening export handlers against closed-pipe errors, and orchestrating clean background flusher goroutine lifecycles.

- **[Entros Protocol Executor Node](https://github.com/entros-protocol/executor-node)** (`Rust`) &dash [PR #12](https://github.com/entros-protocol/executor-node/pull/12)  
  Engineered a lock-free status and metrics layer using `AtomicU64` for high-throughput Axum handlers, implemented constant-time credential verification (`subtle::ConstantTimeEq`) against timing attacks, and introduced TTL-based balance caching.

---

## Selected Systems & Projects

| Project                                                                         | Description                                                                                                                                                                             | Stack                                      |
| :------------------------------------------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------- |
| **[Aks IDE](https://github.com/Akash-Kumar-Sinha/Aks_ide)**                     | Cloud development environment delivering low-latency terminal interaction and execution inside isolated Docker containers via WebSockets and Monaco.                                    | Rust, Docker, WebSockets, Monaco           |
| **[Terminal Emulator](https://github.com/Akash-Kumar-Sinha/terminal-emulator)** | GPU-accelerated terminal emulator written in Rust focused on hardware-accelerated text rendering with low latency.                                                                      | Rust, WGPU, GPU Acceleration               |
| **[Akssora Search](https://github.com/Akash-Kumar-Sinha/Akssora-search)**       | Multimodal media search engine for searching inside videos using visual embeddings and transcripts (_"grep for media"_).                                                                | Python, Embeddings, Vector Search          |
| **[Akssora UI](https://ui.akssora.com/)**                                       | Production-ready React component library with 60+ animated, accessible components designed for performance and zero bundle bloat.                                                       | React, TypeScript, Tailwind CSS, Motion    |
| **[Autograd Engine](https://github.com/Akash-Kumar-Sinha/autograd)**            | Scalar-valued automatic differentiation engine built from scratch with dynamic DAG computation graphs, reverse-mode autodiff via topological sort, and neural network primitives (MLP). | Python, Autodiff, DAG, Deep Learning       |
| **[Candle GPT](https://github.com/Akash-Kumar-Sinha/candle-gpt)**               | Lightweight inference engine for GPT-2 models optimized for resource-efficient transformer execution and parallel processing.                                                           | Rust, Transformers, Inference Engine       |

---

## Technical Writing

In-depth technical writeups on distributed systems, backend internals, and machine learning at [akashkrsinha.com/writing](https://akashkrsinha.com/writing):

- **[Stale-While-Revalidate: Caching Without Latency Spikes](https://akashkrsinha.com/writing/stale-while-revalidation)**  
  Taming thundering herds and cache stampedes with distributed locks and probabilistic early expiration.

- **[Consistent Hashing: Distributing Data Across Servers the Smart Way](https://akashkrsinha.com/writing/consistent-hashing)**  
  Solving modulo resharding cascades and balancing load with virtual nodes.

- **[Designing a Distributed Unique ID Generator](https://akashkrsinha.com/writing/design-a-unique-id-generator-in-distributed-system)**  
  Snowflake bit allocations, clock drift failure modes, and modern UUIDv7 / ULID architectures.

- **[Design a Rate Limiter](https://akashkrsinha.com/writing/rate-limiter)**  
  Algorithms, edge mitigation, and distributed state coordination.

- **[Building an Autograd Engine from Scratch](https://akashkrsinha.com/writing/autograd-engine)**  
  Tensors, computation graphs, chain rule propagation, and training neural networks from first principles.

---

## Core Competencies

- **Languages:** Go, Rust, Python, TypeScript, SQL, C++
- **Distributed Systems & Storage:** Redis, PostgreSQL, Kafka, WebSockets, Microservices, Lock-free Concurrency
- **Infrastructure & Reliability:** Docker, Kubernetes, Linux, Terraform, CI/CD, Prometheus, Grafana
- **Web & Frameworks:** Axum, Gin, React, Next.js, Tailwind CSS

---

- **Currently Learning - AI:** Reverse-mode Autodiff, Transformer Inference, Embeddings, Neural Networks, PyTorch, Hugging Face, NLP, Computer Vision, Reinforcement Learning, DDPM

---

## Contact

- **Website:** [akashkrsinha.com](https://akashkrsinha.com)
- **Writing:** [akashkrsinha.com/writing](https://akashkrsinha.com/writing)
- **Schedule a Call:** [cal.com/akash-krsinha/15min](https://cal.com/akash-krsinha/15min)
- **Email:** [aks.krsinha@gmail.com](mailto:aks.krsinha@gmail.com)
- **LeetCode:** [leetcode.com/u/akash_krsinha](https://leetcode.com/u/akash_krsinha/)
