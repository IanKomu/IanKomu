# Ian Komu
**DevOps Engineer & Backend Developer · Nairobi, Kenya**

I build and ship backend systems and infrastructure for financial platforms across Africa — payment gateways, banking integrations, mobile money networks. Currently at InTouch Group, where I bridge software engineering and DevOps to keep critical fintech infrastructure running reliably across Anglophone and Francophone African markets.

My background is backend-first: Spring Boot from my first internship, systems architecture at Ika Three Sixty, now DevOps on distributed fintech infrastructure. I'm building this GitHub to reflect that depth across multiple stacks.

---

## Currently building

A cross-stack portfolio — the same three projects implemented in five languages, so the implementations can be compared directly rather than each one living in its own domain.

### bookstore-api — Production REST API

| Stack | Status |
|---|---|
| Spring Boot | ✅ Live |
| Go | 🔨 In progress |
| Rust | 🔨 In progress |
| JavaScript (Node.js) | 🔨 In progress |
| Python | 🔨 In progress |

### notify-hub — Event-driven notification service

| Stack | Status |
|---|---|
| Spring Boot | ✅ Live |
| Go | 🔨 In progress |
| Rust | 🔨 In progress |
| JavaScript (Node.js) | 🔨 In progress |
| Python | 🔨 In progress |

### fileforge — CLI file processor

| Stack | Status |
|---|---|
| Spring Boot | 🔨 In progress |
| Go | 🔨 In progress |
| Rust | 🔨 In progress |
| JavaScript (Node.js) | 🔨 In progress |
| Python | 🔨 In progress |

The point isn't to build five versions of the same thing. Each language handles the same problem differently — Go's goroutine worker pool, Rust's rayon parallel iterators, Python's multiprocessing Pool — and seeing those differences side by side is the signal.

---

## Stack

**Backend**

Java · Spring Boot · Go · Rust · Python · Node.js

**Frontend**

Next.js · TypeScript · Tailwind CSS

**Infrastructure & DevOps**

Docker · PostgreSQL · Redis · Grafana

---

## Featured projects

### [bookstore-api — Spring Boot](https://github.com/IanKomu/bookstore-api)

Production-grade REST API. JWT auth, role-based access, Flyway migrations, pagination. Books auto-enrich on creation — Google Books pulls cover images, descriptions, page counts, and categories. NYT bestseller lists are cached weekly and served from the local database. Built with the kind of failure handling I care about in production: enrichment never crashes a request, external API outages return graceful empty results.

`Spring Boot 3.2` `Java 21` `PostgreSQL` `Flyway` `JWT` `Docker` `Google Books API` `NYT Books API`

---

### [notify-hub — Spring Boot](https://github.com/IanKomu/notify-hub-springboot)

Event-driven notification service. POST an event, get a 202 immediately — dispatch happens asynchronously on RabbitMQ consumer threads. Email and webhook channels run in parallel with exponential backoff retry (1s → 2s → 4s) and dead-letter handling for exhausted retries. Every delivery attempt is recorded, so the full history is there when something goes wrong at 2am. 61 tests across all layers.

`Spring Boot 3.2` `Java 21` `RabbitMQ` `PostgreSQL` `Flyway` `Docker` `Spring Retry`

---

## Background

Started as a Spring Boot intern building REST APIs and tuning Hibernate queries. Moved into systems architecture — real-time data sync between enterprise platforms, middleware APIs replacing manual workflows. Now DevOps on fintech infrastructure that crosses borders: deploying microservices, owning CI/CD pipelines, monitoring distributed systems with Grafana.

Every role has been about making systems more reliable, more connected, and faster to ship.

---

## Connect

[LinkedIn](https://linkedin.com/in/ian-komu) · [GitHub](https://github.com/IanKomu)
