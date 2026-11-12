# Jesús Ocanto

**Full-Stack Software Engineer**  
I design and build production web platforms, asynchronous backend services, and cross-platform mobile applications using **Python**, **TypeScript**, and **Go**.

[Portfolio](https://portfolio-five-drab-34.vercel.app) · [LinkedIn](https://www.linkedin.com/in/jesus-ocanto) · [yisusocanto1984@gmail.com](mailto:yisusocanto1984@gmail.com)

---

### Engineering Focus

- **Backend & Systems:** Designing modular REST APIs (`Router -> Service -> Repository`), asynchronous data layers (`SQLAlchemy` / `SQLModel`, `AsyncPG`), caching and rate-limiting strategies (`Redis`), and concurrent services in **Python**, **Node.js (NestJS)**, and **Go**.
- **Frontend & Mobile:** Building fast, type-safe interfaces with **Next.js (App Router)**, **React**, **Astro**, and **React Native (Expo)** with **Tailwind CSS**.
- **Database & Infrastructure:** Relational data modeling in **PostgreSQL**, schema migrations (`Alembic`, `Prisma`), object storage (`Cloudflare R2`), containerization (`Docker`), and automated CI/CD pipelines (`GitHub Actions`).

---

### Selected Open-Source Projects

#### [Pixel Reviews (v2)](https://pixelreviews.vercel.app) — Social Discovery & Review Platform for Video Games
Full-stack community platform re-engineered from the ground up with a decoupled architecture. Features on-demand game metadata hydration via **IGDB API v4**, 5-to-1 star rating histograms, threaded discussions, wishlists, dual JWT + Google OAuth 2.0 authentication with automatic token rotation, and a **Redis** cache-aside layer with fail-open degradation.
- **Stack:** `Next.js 16` · `React 19` · `TypeScript` · `FastAPI` · `PostgreSQL 17` · `Redis 7` · `Cloudflare R2` · `Docker`
- **Links:** [Live Platform](https://pixelreviews.vercel.app) · [Frontend Repo](https://github.com/Yisusocanto/pixel-reviews-frontend) · [Backend API Repo](https://github.com/Yisusocanto/pixel-reviews-api)

#### [Fialo](https://github.com/Yisusocanto/fialo) — Multi-Tenant Mobile Credit & Ledger System
Cross-platform mobile application and backend API built for local merchants to replace paper credit ledgers. Implements strict multi-tenant data isolation, role-based access control with instant session revocation, and exact decimal arithmetic (`Decimal.js`) for accounts receivable tracking.
- **Stack:** `React Native` · `Expo` · `TypeScript` · `NestJS` · `PostgreSQL` · `Prisma` · `NativeWind`
- **Links:** [GitHub Repository](https://github.com/Yisusocanto/fialo) · [Case Study](https://portfolio-five-drab-34.vercel.app/projects/fialo)

#### [Venezuela Tasas](https://venezuela-tasas.vercel.app) & [Telegram Bot](https://github.com/Yisusocanto/venezuela-tasas-bot) — Exchange Rate Engine & Alerting System
Resilient scraping engine, public REST API, web dashboard, and asynchronous Telegram bot delivering real-time and historical official exchange rates (USD, EUR, RUB, TRY) with scheduled daily broadcasts and PostgreSQL subscriber persistence.
- **Stack:** `FastAPI` · `Python` · `Next.js` · `PostgreSQL` · `AsyncPG` · `Telegram API` · `Docker`
- **Links:** [Web App](https://venezuela-tasas.vercel.app) · [Platform Repo](https://github.com/Yisusocanto/venezuela-tasas) · [Bot Repo](https://github.com/Yisusocanto/venezuela-tasas-bot)

---

### Commercial & Enterprise Systems (Production)

| System | Overview | Architecture & Stack | Documentation |
| :--- | :--- | :--- | :--- |
| **Todo Technology — ERP / MES Platform** | End-to-end manufacturing execution system for a large-scale textile and sublimation plant. Synchronizes sales, graphic design, cutting, heat-pressing, sewing, and shipping with QR-driven stage transitions and a dynamic EAV product schema. | `FastAPI` · `Next.js` · `PostgreSQL` · `Docker` | [Read Case Study →](https://portfolio-five-drab-34.vercel.app/projects/todo-technology) |
| **La Parada — Agro-Industrial ERP & POS** | Enterprise resource planning system for a commercial butchery and dairy processing facility. Manages raw milk reception, recipe-driven batch manufacturing with yield tracking, lot-level inventory, and bi-monetary (USD/VES) point-of-sale ledgers. | `FastAPI` · `Next.js` · `TypeScript` · `PostgreSQL` | [Read Case Study →](https://portfolio-five-drab-34.vercel.app/projects/carniceria-la-parada) |

---

### Technical Toolkit

| Layer | Technologies |
| :--- | :--- |
| **Languages** | `Python` · `TypeScript` · `JavaScript` · `Go (Golang)` · `SQL` |
| **Backend** | `FastAPI` · `NestJS` · `Go (net/http, Gin/Chi)` · `Node.js` · `Express` · `SQLModel` · `SQLAlchemy 2.0` · `Prisma` |
| **Frontend & Mobile** | `Next.js (App Router)` · `React 19` · `React Native` · `Expo` · `Astro` · `TanStack Query` · `Tailwind CSS` |
| **Data & Storage** | `PostgreSQL` · `Redis` · `MongoDB` · `Cloudflare R2 (S3)` · `Alembic` |
| **DevOps & Quality** | `Docker` · `Docker Compose` · `GitHub Actions` · `Pytest` · `Vitest` · `Ruff` · `Linux` |
