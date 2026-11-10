# Hi there, I'm Naveen Chandra P 👋

Senior Backend & Systems Engineer specializing in high-throughput microservices, event-driven pipelines, and distributed backend architecture. I build resilient, low-latency applications with **Node.js, NestJS, TypeScript, PostgreSQL, and Redis**.

---

### 💻 Technical Stack & Ecosystem

- **Languages:** TypeScript, JavaScript (Node.js)
- **Frameworks & Runtimes:** NestJS, Express.js
- **Databases & ORMs:** PostgreSQL, Prisma ORM, Redis
- **Messaging & Event Streaming:** Redis Pub/Sub, RabbitMQ
- **Architectural Patterns:** Clean/Hexagonal Architecture, Transactional Outbox, Event-Driven Systems, Database Sharding
- **Tools & Workflows:** Docker, Docker Compose, Git, Cursor IDE (Spec-Driven)

---

### 🏗️ Featured Architecture & Work

#### 1. 🔄 [Transactional Outbox Engine](https://github.com/pncnaveen/transactional-outbox-engine)
> **Stack:** NestJS, PostgreSQL, Prisma, Redis / RabbitMQ
- Resolves dual-write inconsistencies between domain mutations and event publication using single-database interactive transactions (`$transaction`).
- Implements concurrency-safe polling via PostgreSQL row-level locks (`FOR UPDATE SKIP LOCKED`) and exponential backoff retry mechanics.

#### 2. ⚡ [Scalable Notification Gateway](https://github.com/pncnaveen/notification-gateway)
> **Stack:** NestJS, WebSockets (Socket.io), Redis Pub/Sub
- Real-time notification and client presence management system designed for horizontal scaling across multi-node clusters.
- Eliminates state lock-in by delegating socket presence tracking and cross-node event broadcasting to a distributed Redis cache.

#### 3. 🖥️ Monorepo PC Part Picker & Social Engine
> **Stack:** React, Node.js/Express, PostgreSQL, Prisma, Anthropic API
- Full-stack monorepo featuring real-time specs intake, structured schema normalization, and dynamic component compatibility matching.
- Developed using spec-driven, AI-accelerated workflows for high velocity and modular code boundary enforcement.

---

### 📊 Engineering Focus

```text
[ Core Backend Architecture ]  ████████████████████  95%
[ Relational Databases (PG) ]  ███████████████████░  90%
[ Caching & Pub/Sub (Redis) ]  ██████████████████░░  85%
[ System Design & Resilience]  █████████████████░░░  80%
```

---

### 📬 Connect with Me

- **Email:** naveenchandrapremkumar@gmail.com
- **GitHub:** [github.com/pncnaveen](https://github.com/pncnaveen)
- **Services & Bounties:** Open for Backend Engineering contracts, microservice architecture design, and database performance optimization.
