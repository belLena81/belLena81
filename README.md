👋 Hi, I'm Olena Biloshapka

Backend engineer working at the intersection of distributed systems and AI. I architect and build scalable Scala/Go services - from regulated, high-load production platforms to open-source RAG and LLM tooling.
Before engineering, I spent 18 years as a Research Scientist building computational models of industrial processes. That background shows up in how I work now: model the system before you build it, validate every assumption, design for failure modes up front.

🧠 Featured Projects

RAGlibrarian

A cloud-native RAG platform that turns a private technical library (PDF/EPUB) into a hallucination-resistant, citation-backed knowledge base — page-level evidence, not just a plausible-sounding answer.
Distributed, event-driven microservices (Clean Architecture, DDD)
Multi-stage retrieval: vector search + full-text search + metadata filtering + LLM reranking
Service boundaries and async communication via gRPC and RabbitMQ
Secure auth with PASETO, mTLS, and role-based access control
Go gRPC RabbitMQ PostgreSQL Qdrant MinIO Docker CQRS RAG

DevMate

A local-first CLI that generates commit messages, branch names, and PR descriptions from your repo state, using a locally running LLM via Ollama. Fully offline, read-only, no auto-applied Git mutations.
Map-reduce pipeline for large diffs: chunking → parallel summarisation → hierarchical reduction
Content-addressed caching (SHA256) with automatic invalidation
Concurrency tuned for CPU inference: semaphores, timeouts, retry with backoff
Clean/Hexagonal architecture with domain interfaces like GitClient, LLM, Cache
Cobra-based CLI, dependency injection, built for easy testing and extension
Go CLI Ollama LLM (local inference) Cobra Hexagonal Architecture

💼 What I Work On
Most of my production work is under client NDA, but it spans:
Distributed, event-driven backend platforms at scale (millions of events/day)
RAG, semantic search, and LLM-driven workflows over private document collections
High-compliance, regulated systems (public sector, financial/tax integrations)
Scala ecosystem migrations and long-term maintainability (2.12→2.13, ZIO 1→2)
API integrations across telephony, payments, banking, and third-party platforms

🚀 Tech Stack
Languages — Scala, Go, Java, C++ 
Backend — Akka, ZIO, Cats/Cats Effect, Play Framework, Slick 
API — REST, GraphQL (Caliban), gRPC, Protobuf 
Data — PostgreSQL, MongoDB, Cassandra, Qdrant 
Messaging & Search — Kafka, RabbitMQ, Elasticsearch 
Cloud & Infra — AWS, Docker 
AI/LLM tooling — RAG pipelines, local inference (Ollama), embedding & vector search 
Other — Scala.js, FreeSWITCH, ScalaTest/JUnit

📫 Open to interesting distributed-systems, backend, or RAG/LLM work - feel free to reach out via GitHub.

