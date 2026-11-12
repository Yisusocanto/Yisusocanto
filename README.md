# Jesús Ocanto

**Full-Stack & Backend Software Engineer**  
I design and build production web platforms, asynchronous APIs, concurrent network services, and cross-platform mobile applications using **Python**, **TypeScript**, and **Go**.

[Portfolio](https://portfolio-five-drab-34.vercel.app) · [LinkedIn](https://www.linkedin.com/in/jesus-ocanto) · [yisusocanto1984@gmail.com](mailto:yisusocanto1984@gmail.com)

---

### Engineering Focus

- **Backend & Distributed Systems:** Modular REST APIs (`Router -> Service -> Repository`), asynchronous data access (`SQLModel`, `SQLAlchemy 2.0`, `AsyncPG`), caching & rate-limiting (`Redis`), and concurrent network services in **Python**, **TypeScript (NestJS)**, and **Go**.
- **Frontend & Mobile:** High-performance, type-safe interfaces built with **Next.js (App Router)**, **React**, **Astro**, and **React Native (Expo)**.
- **Data & Infrastructure:** Complex relational modeling in **PostgreSQL**, schema migrations (`Alembic`, `Prisma`), S3-compatible storage (`Cloudflare R2`), containerization (`Docker`), and automated CI pipelines (`GitHub Actions`).

---

### Flagship Open-Source Projects

#### [Pixel Reviews (v2)](https://pixelreviews.vercel.app) — Video Game Discovery & Community Review Platform
Full-stack social platform re-engineered from the ground up with a decoupled architecture. Features on-demand metadata hydration via **IGDB API v4**, 5-to-1 star rating histograms, threaded discussions, wishlists, dual JWT + Google OAuth 2.0 authentication with automatic token rotation, and a **Redis** cache-aside layer with fail-open degradation.
- **Stack:** `Next.js 16` · `React 19` · `TypeScript` · `FastAPI` · `PostgreSQL 17` · `Redis 7` · `Cloudflare R2` · `Docker`
- **Links:** [Live Platform](https://pixelreviews.vercel.app) · [Frontend Repo](https://github.com/Yisusocanto/pixel-reviews-frontend) · [Backend API Repo](https://github.com/Yisusocanto/pixel-reviews-api)

#### [Fialo](https://github.com/Yisusocanto/fialo) — Multi-Tenant Mobile Credit & Ledger System
Cross-platform mobile application and backend API built for local merchants to digitize customer credit accounts. Implements strict multi-tenant data isolation, role-based access control with instant session revocation, and exact decimal arithmetic (`Decimal.js`) for financial ledgers.
- **Stack:** `React Native` · `Expo` · `TypeScript` · `NestJS` · `PostgreSQL` · `Prisma` · `NativeWind`
- **Links:** [GitHub Repository](https://github.com/Yisusocanto/fialo) · [Case Study](https://portfolio-five-drab-34.vercel.app/projects/fialo)

#### [Venezuela Tasas](https://venezuela-tasas.vercel.app) & [Telegram Bot](https://github.com/Yisusocanto/venezuela-tasas-bot) — Exchange Rate Engine & Alerting System
Automated scraping engine, public REST API, web dashboard, and asynchronous Telegram bot delivering real-time and historical official exchange rates (USD, EUR, RUB, TRY) with scheduled daily broadcasts and PostgreSQL subscriber persistence.
- **Stack:** `FastAPI` · `Python` · `Next.js` · `PostgreSQL` · `AsyncPG` · `Telegram API` · `Docker`
- **Links:** [Web App](https://venezuela-tasas.vercel.app) · [Platform Repo](https://github.com/Yisusocanto/venezuela-tasas) · [Bot Repo](https://github.com/Yisusocanto/venezuela-tasas-bot)

---

### Systems & Networking in Go

| Project | Engineering Highlights | Stack | Repository |
| :--- | :--- | :--- | :--- |
| **HTTP Reverse Proxy & Load Balancer** | Concurrent round-robin load balancer built with Go's standard library (`net/http/httputil`). Features lock-free health state via `sync/atomic.Bool`, transparent request retries on node failure, active background health-check goroutines, and graceful shutdown. | `Go` · `net/http` · `sync/atomic` | [Yisusocanto/reverse-proxy](https://github.com/Yisusocanto/reverse-proxy) |
| **Chatime — Concurrent TCP Chat Server** | Multi-client real-time TCP server (`net.Listener`) with per-connection goroutines, thread-safe state synchronization (`sync.RWMutex`), custom slash-command routing, idle connection deadlines, and a dedicated terminal client. | `Go` · `TCP Sockets` · `sync.RWMutex` | [Yisusocanto/chatime](https://github.com/Yisusocanto/chatime) |

---

### Commercial & Enterprise Systems (Production)

| System | Overview | Stack | Case Study |
| :--- | :--- | :--- | :--- |
| **Todo Technology — ERP / MES Platform** | End-to-end manufacturing execution system for a large-scale textile and sublimation plant. Synchronizes sales, design, cutting, heat-pressing, sewing, and shipping with QR-driven transitions and a dynamic EAV product schema. | `FastAPI` · `Next.js` · `PostgreSQL` · `Docker` | [Read Case Study →](https://portfolio-five-drab-34.vercel.app/projects/todo-technology) |
| **La Parada — Agro-Industrial ERP & POS** | Enterprise resource planning system for a commercial butchery and dairy processing plant. Manages raw milk intake, recipe-driven batch manufacturing with yield tracking, lot-level inventory, and bi-monetary (USD/VES) point-of-sale ledgers. | `FastAPI` · `Next.js` · `TypeScript` · `PostgreSQL` | [Read Case Study →](https://portfolio-five-drab-34.vercel.app/projects/carniceria-la-parada) |

---

### Technical Toolkit

| Layer | Technologies |
| :--- | :--- |
| **Languages** | `Python` · `TypeScript` · `Go (Golang)` · `JavaScript` · `SQL` |
| **Backend** | `FastAPI` · `NestJS` · `Go (net/http, TCP)` · `Node.js` · `Express` · `SQLModel` · `SQLAlchemy 2.0` · `Prisma` |
| **Frontend & Mobile** | `Next.js (App Router)` · `React 19` · `React Native` · `Expo` · `Astro` · `TanStack Query` · `Tailwind CSS` |
| **Data & Storage** | `PostgreSQL` · `Redis` · `MongoDB` · `Cloudflare R2 (S3)` · `Alembic` |
| **DevOps & Quality** | `Docker` · `Docker Compose` · `GitHub Actions` · `Pytest` · `Vitest` · `Ruff` · `Linux` |
