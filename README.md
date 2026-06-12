# Rohan Kuckian

***M.S. Computer Science @ Stony Brook University*** · ***Systems & Backend Engineer*** · ***Distributed Systems***

---

## About

Software engineer with **2+ years** of industry experience building high-availability backend systems at scale. Currently architecting **high-throughput data pipelines and web infrastructure** as a Graduate Research Assistant at Stony Brook. Deeply passionate about **distributed systems architecture**, **event-driven pipelines**, and fault-tolerant infrastructure.

📍 Stony Brook, NY &nbsp;|&nbsp; 📬 rohan.kuckian@gmail.com &nbsp;|&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/rohan-kuckian-865196191/)

---

## 🛠 Tech Stack

**Languages**
`Go (Golang)` `Java` `Python` `SQL` `PL/SQL` `TypeScript` `JavaScript` `C/C++`

**Distributed Systems & Messaging**
`Apache Kafka` `gRPC` `Multi-Paxos` `Two-Phase Commit (2PC)` `Event-Driven Architecture` `Distributed Locking` `Write-Ahead Logging (WAL)`

**Databases & Caching**
`PostgreSQL` `Redis` `Oracle 19c` `MySQL` `MongoDB` `BoltDB` `DynamoDB`

**Cloud & DevOps**
`AWS (EKS, EC2, S3, Lambda, SQS)` `Docker` `Kubernetes` `Terraform` `Nginx` `CI/CD (GitHub Actions, GitLab)` `Git`

**Frameworks & Libraries**
`FastAPI` `Next.js` `React` `Tailwind CSS` `Pandas` `NumPy` `PyTorch` `LangChain`

---

## Experience

### Graduate Research Assistant — *Stony Brook University*
`Jan 2025 – May 2026` · Python · Next.js · Tailwind CSS · Docker · Nginx · AWS (EC2) · Pandas

- **Architected high-throughput data pipelines** in Python utilizing vectorized Pandas operations to process a **100M+** record dataset, boosting ingestion and processing throughput by **50%**.
- **Engineered an automated, 8-thread distributed scraper** using the BlueSky API for daily data archival; containerized and deployed the stack on AWS EC2 using Docker and Nginx reverse proxying.
- **Orchestrated the containerization and migration** of 11 legacy multi-language applications into a centralized infrastructure, cutting server overhead and modernizing state management.
- **Developed a dynamic, fully responsive full-stack web application** utilizing Next.js and Tailwind CSS for data visualization, optimizing real-time state synchronization across modular UI components.

---

### Associate Consultant (Software Engineer) — *Oracle Financial Services Software (OFSS)*
`Jun 2022 – Jun 2024` · Java · PL/SQL · Oracle 19c · REST APIs · Microservices · Git · Agile

- **Developed high-availability backend services** for Flexcube core banking systems deployed globally, directly supporting transaction engines processing **20M+ daily transactions**.
- **Optimized high-volume processing pipelines** by engineering custom PL/SQL packages, advanced database indexes, and query joins to handle **1M+ daily records**, reducing manual operational workload by **40%**.
- **Architected and deployed RESTful microservices** to integrate 3 distinct core banking models; optimized payload schemas to reduce network data overhead, achieving a **4x acceleration** in API delivery frequency.
- **Diagnosed and mitigated 10–20 high-priority production and UAT bugs** daily under strict SLA metrics, ensuring system stability and zero-downtime customer handovers.
- **Leveraged non-linear data structures** (advanced tree variations and graph-based routing models) to resolve complex, multi-level branching business logic for mission-critical financial calculations.

---

## Projects

### Financial Fraud Platform (Active Development)
`Go` · `Apache Kafka` · `Redis` · `PostgreSQL` · `AWS EKS` · `FastAPI` · `LLMs / RAG`

- **Designing a production-grade distributed streaming platform** to ingest **8,000+ events/sec** via a Go REST API (Gin), routing live transactional streams through high-throughput Apache Kafka broker clusters.
- **Implementing ultra-low latency fraud detection (<5ms)** utilizing Redis sliding window counters to track rate-based transaction velocity and maintain a target p99 API latency under 40ms.
- **Enforcing system correctness guarantees** by integrating unique idempotency keys to prevent database duplication and configuring Kafka consumer groups with a Dead-Letter Queue (DLQ) for automated failure recovery.
- **Configuring cloud infrastructure deployment plans** targeting AWS EKS with Horizontal Pod Autoscaling, automated GitHub Actions CI/CD pipelines, and full-stack observability via Datadog.
- **Integrating an asynchronous Python FastAPI microservice** to execute LLM-powered fraud explanations via a Retrieval-Augmented Generation (RAG) pipeline utilizing LangChain and ChromaDB.

### Distributed Transaction Processor
`Go` · `Multi-Paxos` · `Two-Phase Commit (2PC)` · `BoltDB` · `gRPC` · `Protobuf`

- **Built a sharded, fault-tolerant distributed key-value store** in Go supporting atomic read-only, intra-shard, and cross-shard transactions across multi-node clusters.
- **Implemented Multi-Paxos** for intra-shard consensus and **Two-Phase Commit (2PC)** for cross-shard atomicity, deploying Write-Ahead Logging (WAL) and distributed locking to preserve absolute ACID compliance.
- **Developed an index-based dynamic resharding framework** and a custom benchmarking system, achieving a peak performance throughput of **1,038 transactions/sec** under intensive workload skew.

### BagLocater
`React Native` · `Django` · `MongoDB` · `Python` · `AES Encryption`

- **Architected cross-platform mobile and desktop infrastructure** using Django and MongoDB to handle real-time synchronization pipelines between transit clients and airport staff.
- **Optimized backend data transport layers**, accelerating image fetch latencies by **20x** and sustaining a secure desktop interface response time of **<100ms**.
- **Secured payload transit pipelines** by implementing AES encryption standards, mitigating data leakage risks, and ensuring **90%+** user identity data protection across storage nodes.

---

## Education

**M.S. Computer Science** — Stony Brook University *(GPA: 3.77 / 4.0)* · 2024–2026
> Distributed Systems · Analysis of Algorithms · Data Science Fundamentals · HCI · NLP

**B.E. Information Technology** — University of Mumbai · 2018–2022
> Databases · Web Development · Software Engineering · Artificial Intelligence
