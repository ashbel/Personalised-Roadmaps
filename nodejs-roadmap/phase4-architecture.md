# Phase 4 – Architecture & Scalability
## Goals
- Learn clean architecture patterns for Node.js applications (domain‑driven design, hexagonal architecture, layered architecture).
- Understand microservices vs monolith and decide when to decompose services; manage modular monorepos.
- Explore multi‑tenancy patterns for serving multiple customers with shared or isolated resources.
- Implement event‑driven architecture for decoupled services using message brokers (e.g. RabbitMQ, Kafka).

## Topics & Resources
- **Clean Architecture & DDD**: Study principles of domain‑driven design and hexagonal architecture; resources: [Clean Architecture book](https://www.oreilly.com/library/view/clean-architecture/9780134494272/) and blog posts.
- **Monorepo Management**: Tools like Nx or TurboRepo for managing multi‑package repositories.
- **Microservices & Service Decomposition**: Patterns like API gateway, service discovery, circuit breakers; reading: microservices patterns by Chris Richardson.
- **Multi‑tenancy**: Strategies such as database‑per‑tenant vs shared database; row‑level scoping and schema isolation.
- **Event‑Driven & Messaging**: Basics of message brokers (RabbitMQ, Kafka), publish–subscribe patterns, idempotency and retries.
- **Security & Performance**: Rate limiting, caching strategies, load balancing, and monitoring.

## Practice Tasks
- Refactor the backend API from Phase 2 into modular layers following clean architecture; separate domains (e.g. products, orders, notifications) and move business logic into services.
- Investigate multi‑tenant designs for your POS/notifications system; implement a basic multi‑tenant layer (e.g. tenant ID in requests, row‑level security).
- Build a simple event‑driven component: when an order is placed, publish an event and consume it in a notification service. Start with Node.js EventEmitter or a lightweight broker like NATS; later experiment with RabbitMQ or Kafka locally.
- Document your architecture decisions using C4 or similar diagrams; include diagrams of the system context, containers and components.

## Deliverables
- A `phase4-architecture` subfolder containing design documents, diagrams, and refactored code following clean architecture principles.
- Code samples or microservices demonstrating service decomposition or modularization.
- Implementation of a basic event‑driven messaging workflow.
- A write‑up describing multi‑tenancy approaches and the one you implemented.
