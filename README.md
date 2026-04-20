# Hi there, I'm Aqib Hussain 👋

**Senior Full Stack Engineer** · 4+ years · Node.js • NestJS • React.js • Next.js • TypeScript • PostgreSQL • AWS  
Building scalable, enterprise-grade systems for clients across **Pakistan, the US, Canada, and Europe** · Open Source Contributor

---

## 🚀 What I Build

- ⚙️ High-throughput backend APIs — Node.js, NestJS, Express, **Go (Gin)**, **Java (Spring Boot)**
- 🎯 Modern frontends — React.js, Next.js, Angular, Redux Toolkit, Tailwind, MUI
- 🧠 LLM integration & RAG pipelines — OpenAI, Claude (Anthropic), prompt engineering, agentic workflows
- 🤖 MCP (Model Context Protocol) server tooling and AI-integrated platforms
- 🔄 Event-driven microservices — Redis pub/sub, BullMQ, Socket.io, WebSockets
- ☁️ Cloud-native deployments — AWS (EC2, S3, Lambda), Docker, GitHub Actions CI/CD
- 🔐 Secure, observable systems — JWT + RBAC, OAuth 2.0, multi-tenant isolation, audit trails

---

## 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| **Languages** | TypeScript, JavaScript (ES6+), Go (Golang), Java, Python, SQL |
| **Frontend** | React.js, Next.js, Angular, Vue.js, Redux Toolkit, React Query, Zustand, Tailwind CSS, MUI, PWA |
| **Backend** | Node.js, NestJS, Express.js, Spring Boot, REST, GraphQL, WebSocket, Socket.io, Microservices |
| **Databases** | PostgreSQL, MongoDB, MySQL, Redis, TypeORM, Mongoose |
| **DevOps / Cloud** | AWS (EC2, S3, Lambda), Docker, GitHub Actions, Jenkins, CI/CD, Nginx |
| **Testing** | Jest, React Testing Library, Unit / Integration / E2E pipelines |
| **AI / LLM** | OpenAI (ChatGPT API), Claude (Anthropic), RAG, Prompt Engineering, MCP SDK |
| **Integrations** | Stripe, InovoPay, Brex, OAuth 2.0, KYC/RADAR, Equibase, SendGrid, Keycloak, Puppeteer |

---

## 🌟 Professional Experience

### Senior Software Engineer — Antematter.io *(Aug 2024 – Present)*
`Islamabad, Pakistan`

- Architected and delivered **5+ enterprise applications** using Node.js, NestJS, and React.js for US, Canadian, and European clients with full end-to-end ownership
- Designed high-concurrency REST and WebSocket APIs; **reduced production defects 70%** via automated Jest CI/CD pipelines covering unit, integration, and E2E layers
- Optimised PostgreSQL and MongoDB via composite indexing, execution plan analysis, and Redis caching — achieving **sub-100ms response times** under sustained load
- Implemented **event-driven microservices** (Redis pub/sub + Socket.io) for real-time data synchronisation across distributed services
- Integrated Stripe, InovoPay, Brex, OAuth 2.0, KYC/RADAR, and Equibase APIs into multiple production platforms
- Mentored **5–8 engineers** via structured code reviews, architectural guidance, and best-practice workshops

---

### Tech Lead – Software Engineer — Status200 *(Aug 2023 – Aug 2024)*
`Lahore, Pakistan`

- Led backend architecture for scalable **multi-tenant SaaS enterprise systems** built with NestJS and Express.js
- Designed JWT + RBAC with refresh token rotation and row-level multi-tenant data isolation
- Improved throughput **40%+** via Redis caching and DB read replicas; reduced API latency **35%** through N+1 elimination and ORM query refactoring
- Engineered **BullMQ background queues** for async report generation, email dispatch, and scheduled data sync
- Established Dockerized CI/CD pipelines (GitHub Actions) enabling zero-downtime production deployments
- Led and mentored a backend squad of **4–6 engineers**

---

### Software Engineer — QLU.AI *(Jul 2022 – Aug 2023)*
`Islamabad, Pakistan`

- Developed full-stack features using React.js, NestJS, Python, PostgreSQL, and MongoDB in Agile sprint teams
- Implemented secure auth flows — JWT, bcrypt, OAuth 2.0 social login, and token invalidation — for production SaaS platforms
- Delivered sprint-committed features with comprehensive test coverage across product, design, and QA teams

---

## 🔨 Key Projects

### 🧰 [GinKit](https://github.com/AqibTuri/GinKit) — Production Go + Gin Backend Template
*Public template · Go · PostgreSQL · JWT · Swagger · Docker · GitHub Actions CI*

A batteries-included **Go REST API starter kit** built for real projects — wired end-to-end with everything a production backend actually needs:

- **PostgreSQL + GORM** with versioned SQL migrations (golang-migrate) as schema source of truth
- **JWT auth** with bcrypt, HttpOnly cookie + Bearer fallback, and role-based guards (admin-only routes)
- **Modular feature layout** — DTO + presenter + handler per vertical slice, wired from a single `internal/app` entry point
- **Per-IP rate limiting**, panic recovery, and request ID middleware out of the box
- **Swagger / OpenAPI** UI generated from handler comments (`make swagger`)
- **GitHub Actions CI** that boots a real Postgres service, runs migrations, and executes `go test`
- Full companion docs: `ARCHITECTURE.md`, `LEARNING.md`, `EXPLAINER.md`

> `Go` · `Gin` · `GORM` · `PostgreSQL` · `JWT` · `bcrypt` · `golang-migrate` · `Swagger` · `Docker Compose` · `GitHub Actions`

---

### 📦 [NodeJsTemplate](https://github.com/AqibTuri/NodeJsTemplate) — Node.js + Express MVC Starter
*Public · JavaScript · Express · MongoDB · JWT · MVC*

A clean, no-frills **Node.js REST API boilerplate** in pure JavaScript — structured for real projects from day one:

- Classic **MVC layout** — `controllers`, `routes`, `models`, `middleware`, `config` as first-class folders
- **Express.js** HTTP layer with organized route registration and environment-based config
- **MongoDB** integration via Mongoose with JWT authentication middleware
- Minimal, hackable foundation — clone and ship, no framework lock-in

> `JavaScript` · `Node.js` · `Express` · `MongoDB` · `JWT` · `MVC`

---

### ☕ Spring Boot Backend Template *(In Progress)*
*Java · Spring Boot · PostgreSQL · Spring Security · JWT · Docker*

A production-ready **Java Spring Boot** backend template currently under active development — bringing the same batteries-included philosophy of GinKit to the Java ecosystem. Layered architecture (Controller → Service → Repository), Spring Security with JWT, JPA/Hibernate with PostgreSQL, and Docker Compose setup.

> `Java` · `Spring Boot` · `Spring Security` · `PostgreSQL` · `JPA` · `Docker`

---

### 🐎 Stable Stakes — Real-Time Fantasy Gaming Platform
`Stack: Next.js · NestJS · PostgreSQL · Redis · AWS · Socket.io`

- Designed and built the full product from the ground up — SSR Next.js frontend, NestJS RESTful API, PostgreSQL schema, Redis caching — serving a high-traffic fantasy horse-racing audience
- Engineered a **WebSocket gateway** (Socket.io) delivering live race updates and leaderboard streaming to thousands of concurrent users with **sub-200ms latency**
- Unified Equibase (live racing data), Stripe + InovoPay (payments), Brex (financial ops), RADAR (geofencing compliance), and KYC into a single fault-tolerant service layer
- Built an **ML inference integration layer** feeding player statistics into predictive models with interactive performance dashboards
- Deployed on AWS EC2 with Docker, GitHub Actions CI/CD, blue-green deployments — sustaining **99.9% uptime**

---

### 🏥 Enable Life Care — Medical E-Commerce & Compliance System
`Stack: NestJS · React.js · MongoDB · Stripe · ChatGPT API`

- Built a full-featured medical equipment e-commerce platform for Australian healthcare providers — product catalogue, order management, inventory control, and compliance document generation
- Designed and implemented a **ChatGPT-powered report generation API** using prompt engineering and structured output validation — cutting manual report-writing effort by **60%**
- Integrated Stripe multi-plan billing; implemented JWT + RBAC, audit trail logging, and PII data isolation for regulatory compliance
- Achieved **99.9% uptime** through automated integration test suites and staged rollouts

---

### 📧 QMail — Outreach Automation Platform
`Stack: Node.js · Python · WebSocket · D3.js · Leaflet · PostgreSQL`

- Engineered an end-to-end outreach automation system for LinkedIn and email campaigns — campaign creation, contact management, sequence automation, reply detection, and analytics
- Built a **WebSocket-powered in-app messaging system** with message persistence, read receipts, and typing indicators
- Developed **interactive geospatial analytics** using D3.js and Leaflet — engagement heatmaps, time-zone performance breakdowns, funnel conversion metrics
- Achieved **sub-second response times for 1,000+ concurrent users** through query optimisation, connection pooling, and indexed query plans

---

### 🌍 PinXGlobal — International Exchange Platform
- Architected secure, scalable APIs for global users with Solana token support
- Built frontend with Next.js and modern state management; focused on performance and seamless UX at scale

---

### 🤖 Baker's Bot — High-Frequency Trading Bot
- Backend for a high-frequency automated trading system with Stripe payments, AWS infrastructure, and real-time processing
- Built admin panel and automation workflows with full observability

---

## 🐍 Open Source Contributions

I actively contribute to Python open source in the **ML tooling** and **MCP (Model Context Protocol)** ecosystems.

---

### [`sktime/sktime-mcp`](https://github.com/sktime/sktime-mcp) — MCP Server for Time Series ML

**sktime-mcp** exposes sktime's time series capabilities to LLM agents via the Model Context Protocol.

**Bug fix — `evaluate_estimator_tool` cv_folds enforcement** · `[BUG]`

The `cv_folds` parameter was silently ignored — `ExpandingWindowSplitter(step_length=1)` produced more folds than requested, causing the bundled test to fail on a clean install (`assert 4 == 2`). Fixed by capping results via `results.head(cv_folds)` and added a parametrized regression test covering `cv_folds ∈ {1, 2, 3, 5}`.

> `Python` · `MCP SDK` · `sktime` · `pytest`

### [`sktime/sktime`](https://github.com/sktime/sktime) — Time Series Machine Learning

The leading Python library for time series analysis and machine learning.

**New feature — `SoftEDF1Score` detection metric** · `[ENH]`

Implemented the **SoftED F1 score** (Salles et al., 2024 — *Computers & Industrial Engineering*) as a new detection metric under `sktime.performance_metrics.detection`. Supports linear and rectangular soft-membership functions with a configurable tolerance window, rewarding near-miss event detections proportionally rather than a hard binary match. Full `get_test_params` for the sktime test framework, 7 explicit unit tests, and a worked doctest.

> `Python` · `NumPy` · `pandas` · `sktime` · `time series` · `event detection`

---

## 🎓 Education

**Bachelor of Computer Science** — Sukkur IBA University, Sindh, Pakistan *(Feb 2019 – Feb 2023)*  
Focus: Software Engineering · Sytem Design ·  Algorithms · Database Systems · Web Technologies

---

## 🏅 Certifications

- HackerRank Problem Solving — **Advanced**
- LeetCode — **Advanced**
- Full Stack Development Certification — 2022

---

## 🧩 Engineering Philosophy

I build systems that are:

- **Scalable by design** — engineered for growth from day one
- **Secure by default** — auth, validation, and observability baked in
- **Maintainable for teams** — clean APIs, typed contracts, good docs
- **Optimized for performance** — profiled, measured, and shipped fast

---

## 🌐 Let's Connect

[![Email](https://img.shields.io/badge/Email-aqib.fullstack.engineer%40gmail.com-blue?style=flat-square&logo=gmail)](mailto:aqib.fullstack.engineer@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-aqib--hussain--turi-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/aqib-hussain-turi)
[![Portfolio](https://img.shields.io/badge/Portfolio-aqib--portfolio-black?style=flat-square&logo=vercel)](https://aqib-portfolio-sigma.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-AqibTuri-181717?style=flat-square&logo=github)](https://github.com/AqibTuri)

> 📍 Islamabad, Pakistan · Available immediately · Full-time · On-site / Hybrid / Remote · Open to Gulf & Europe
