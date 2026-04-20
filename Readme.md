# ![Typing Animation](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=F77208&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=100&lines=Electronic+Engineer+%7C+Rust+Developer;Embedded+Systems+%7C+IoT+%7C+Backend)

<p align="justify">"Finally, after having known some interesting languages... I can say that Rust is the only language I want to program with."</p>

```rust
use std::Lang::Rust;
let software_developer = skill.map(|🦀| Rust(🦀)+🚀).collect();
```

<p align="center">
<a href="https://www.linkedin.com/in/felix-manuel-figueroa/"><img alt="Linkedin" width="35px" src="https://img.icons8.com/external-justicon-lineal-color-justicon/64/external-linkedin-social-media-justicon-lineal-color-justicon.png"/></a>&ensp;
<a href="https://twitter.com/FelixM_Figueroa"><img alt="Twitter" width="35px" src="https://img.icons8.com/external-justicon-lineal-color-justicon/64/external-twitter-social-media-justicon-lineal-color-justicon.png"/></a>&ensp;
<a href="https://discord.gg/dYrqe9HZfz"><img alt="Discord" width="35px" src="https://img.icons8.com/external-justicon-lineal-color-justicon/64/external-discord-social-media-justicon-lineal-color-justicon.png"/></a>&ensp;
<a href="https://www.youtube.com/@FelixFigueroa/featured"><img alt="Youtube" width="35px" src="https://img.icons8.com/external-justicon-lineal-color-justicon/64/external-youtube-social-media-justicon-lineal-color-justicon.png"/></a>
</p>

<hr/>

## 🚀 Production & AI Systems — Live at [@leonobitech](https://github.com/leonobitech)

<p align="center">
<a href="https://www.leonobitech.com/"><img alt="Website" src="https://img.shields.io/badge/🌐_leonobitech.com-F77208?style=for-the-badge&logoColor=white"/></a>&ensp;
<a href="https://github.com/leonobitech"><img alt="GitHub Org" src="https://img.shields.io/badge/@leonobitech-181717?style=for-the-badge&logo=github&logoColor=white"/></a>&ensp;
<img alt="Status" src="https://img.shields.io/badge/status-live_in_production-success?style=for-the-badge"/>&ensp;
<img alt="Experience" src="https://img.shields.io/badge/1%2B_year_shipping-green?style=for-the-badge"/>
</p>

> ### 👀 Want to see all this experience in action?
>
> Everything below runs **live in production** on my own VPS under **[@leonobitech](https://github.com/leonobitech)** — my startup, where I ship **production AI automation for SMB clients in LATAM**.
>
> The flagship is a **complete agent stack for sales and customer service**:
> - 💬 **WhatsApp sales agent** that qualifies leads
> - 📅 **Booking agent** that schedules meetings and generates payment links
> - 🧩 All orchestrated through **custom MCP servers I built** to connect Claude with client infrastructure: **Odoo CRM · Qdrant (RAG) · n8n · Docker**
>
> 🔗 **[leonobitech.com](https://www.leonobitech.com/)** · **[@leonobitech on GitHub](https://github.com/leonobitech)**

### 🎯 Quick Access — Production Repos

#### Product Core — The platform itself

| Repo | Stack | Role |
|------|-------|------|
| 🎨 [**frontend**](https://github.com/leonobitech/frontend) | Next.js · TypeScript | Customer-facing UI |
| ⚙️ [**backend**](https://github.com/leonobitech/backend) | Node · TypeScript · Hexagonal | Core API |
| 🔌 [**hardware**](https://github.com/leonobitech/hardware) | Rust · ESP32-C3 · ESP-IDF | IoT firmware with Secure Boot |
| 🎙️ [**agents**](https://github.com/leonobitech/agents) | Python · Realtime | Voice AI agents framework |

#### AI / MCP / Automation — The intelligence layer

| Repo | Description |
|------|-------------|
| 🧩 [**mcp-infrastructure**](https://github.com/leonobitech/mcp-infrastructure) | Custom MCP servers connecting Claude Code ↔ VPS (SSH, n8n, Baserow, Notion) — operating 30 containers via natural language |
| 🔥 [**fullstack-mcp-playground**](https://github.com/leonobitech/fullstack-mcp-playground) ⭐ | Fullstack AI agent template — Claude + microservices + modular tools from UI gallery |
| 🛰️ [**remote-connector-claude**](https://github.com/leonobitech/remote-connector-claude) | Remote MCP Connector for Claude Desktop |

#### Stack Blueprints — Reusable infrastructure

| Repo | Stack |
|------|-------|
| 🐳 [**fullstack-infrastructure-blueprint**](https://github.com/leonobitech/fullstack-infrastructure-blueprint) | Docker · Traefik · HTTPS grid |
| 🎨 [**fullstack-frontend-core**](https://github.com/leonobitech/fullstack-frontend-core) | Next.js 15 · TS (ESM) · Docker |
| ⚙️ [**fullstack-backend-core**](https://github.com/leonobitech/fullstack-backend-core) | Hexagonal API · Node · TS · ESM |

#### Domain-specific (Argentina fiscal compliance)

| Repo | Description |
|------|-------------|
| 🇦🇷 [**l10n_ar_arca_edi**](https://github.com/leonobitech/l10n_ar_arca_edi) | Odoo 19 · ARCA Electronic Invoicing (WSAA/WSFE) |
| 🇦🇷 [**l10n-argentina**](https://github.com/leonobitech/l10n-argentina) | Odoo modules for Argentina |

### 🏗️ What's Running in Production

```
┌─── VPS · 30 containers · Docker Compose · Traefik + Core (auth) ────┐
│                                                                     │
│  🤖 AI / LLM Layer                                                  │
│     • Custom MCP servers   (Odoo · n8n · Baserow · SSH · Notion)    │
│     • Qdrant               (vector DB for RAG pipelines)            │
│     • Voice AI agents      (realtime conversational)                │
│     • n8n                  (1,084 nodes · workflow orchestration)   │
│                                                                     │
│  💼 Business Systems                                                │
│     • Odoo 19              (ERP + Argentina ARCA e-invoicing)       │
│     • Baserow              (no-code DB · 8 tables)                  │
│     • Chatwoot             (customer messaging)                     │
│                                                                     │
│  🚀 Product Stack                                                   │
│     • Frontend             (Next.js 15 · TS · Docker)               │
│     • Backend              (Node · TS · Hexagonal · ESM)            │
│     • Hardware             (ESP32-C3 · Rust · Secure Boot)          │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

### ✅ What I've Shipped

- 🔀 **Agent orchestration & pipelines** — multi-step AI workflows where Claude routes decisions, tools, and data across the client's stack
- 🧪 **API systems** — hexagonal architectures, gRPC services, async Rust backends powering the platform
- 💬 **WhatsApp sales agent** — qualifies leads automatically, live with SMB clients in LATAM
- 📅 **Booking agent** — schedules meetings and generates payment links end-to-end
- 🧩 **Custom MCP servers** connecting Claude with Odoo CRM, Qdrant, n8n, and the VPS (30 containers operated via natural language)
- 🧠 **RAG pipeline** in production with Qdrant for context-aware AI responses
- 📑 **Odoo 19 with AFIP/ARCA e-invoicing** — full fiscal compliance for Argentina
- 🎙️ **Realtime voice AI agents** — conversational interfaces for customers
- 🐳 **30-container VPS** — Docker Compose + Traefik + automatic HTTPS
- 🔌 **IoT firmware (ESP32-C3, Rust)** with Secure Boot for edge deployments
- 📦 **Reusable blueprints** published for fullstack + infra + MCP playgrounds

---

## About Me

**Electronic Engineer** with **6+ years in software engineering** (web, backend, API systems) and **3+ years deep in AI and LLM-based systems** — currently **orchestrating agents and pipelines**, shipping real workflow automation powered by AI.

I work across the stack — **Rust** for embedded + backend (ESP32-C3, Axum, Tokio), **TypeScript / Next.js** for product, and **custom MCP servers** for the AI layer — bridging hardware, software, and AI end-to-end.

My biggest recent bet: launching **[Leonobitech](https://www.leonobitech.com/)**, shipping **production AI automation for SMB clients in LATAM**. [Details in the production section above ↑](#-production--ai-systems--live-at-leonobitech)

## Tech Stack

**Languages & Core**

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

**Embedded & IoT**

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-007B5F?style=for-the-badge&logo=freertos&logoColor=white)

**Backend & Infrastructure**

![Tokio](https://img.shields.io/badge/Tokio-232323?style=for-the-badge)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Leptos](https://img.shields.io/badge/Leptos-EF3939?style=for-the-badge)

---

## Featured Projects

### Rust Embedded / IoT

| Project | Description |
|---------|-------------|
| [**paso-01-scaffold**](https://github.com/FMFigueroa/paso-01-scaffold) | Curso practico de Rust embedded con ESP32-C3 — desde LED blink hasta concurrencia y watchdog management (9 pasos) |
| [**embedded-learning**](https://github.com/FMFigueroa/embedded-learning) | ESP32 embedded systems learning repository — Rust & C |
| [**esp32-essential-training**](https://github.com/FMFigueroa/esp32-essential-training) | ESP32 con ESP-IDF en C — foundation para embedded systems |

### Rust Backend & Systems

| Project | Description |
|---------|-------------|
| [**actor-model-system-in-tokio**](https://github.com/FMFigueroa/actor-model-system-in-tokio) | Actor model para tracking de ordenes con budget threshold — concurrencia con Tokio |
| [**asset-upload-in-Cloudinary**](https://github.com/FMFigueroa/asset-upload-in-Cloudinary) | Sistema asincronico de upload de assets a Cloudinary en Rust |
| [**axum-cookbook**](https://github.com/FMFigueroa/axum-cookbook) | Recetas con Tokio, Hyper, Serde y Tower |
| [**grpc-tonic**](https://github.com/FMFigueroa/grpc-tonic) | Servicio gRPC con Tonic e instrumentacion con Autometrics |

### Rust Educativo

| Project | Description |
|---------|-------------|
| [**functional-programming-in-rust**](https://github.com/FMFigueroa/functional-programming-in-rust) | Tutoriales de fundamentos y aplicaciones avanzadas de programacion funcional en Rust |
| [**sha256-cracker**](https://github.com/FMFigueroa/sha256-cracker) | CLI sha256 cracker — ejercicio de Rust systems programming |
| [**dining-philosophers**](https://github.com/FMFigueroa/dining-philosophers) | Clasico problema de concurrencia implementado en Rust |

### Full Stack

| Project | Description |
|---------|-------------|
| [**blog_post_rust**](https://github.com/FMFigueroa/blog_post_rust) | Full-Stack web application con Rust y Leptos |
| [**superheroes**](https://github.com/FMFigueroa/superheroes) | Sistema de autenticacion y control de acceso con Redux — Next.js |
