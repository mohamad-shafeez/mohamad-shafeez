<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:020810,30:051528,70:0a2a4a,100:00b4d8&height=220&section=header&text=Mohamad%20Shafeez&fontSize=58&fontColor=ffffff&fontAlignY=40&fontAlign=50&desc=Backend%20Engineer%20%E2%80%A2%20AI%20Systems%20%E2%80%A2%20Real-Time%20Architectures&descAlignY=62&descSize=17&descColor=7dd3fc&animation=fadeIn" />

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=800&color=00B4D8&center=true&vCenter=true&multiline=false&width=700&lines=Building+fault-tolerant+AI+runtimes;Architecting+real-time+backend+systems;Generating+production+DevOps+infrastructure+with+AI;Designing+production-ready+software+systems)](https://git.io/typing-svg)

</div>

<br/>

<div align="center">

<a href="https://linkedin.com/in/mohamad-shafeez">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117"/>
</a>
&nbsp;
<a href="mailto:shafeezchappi18@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-shafeezchappi18-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117"/>
</a>
&nbsp;
<a href="https://github.com/mohamad-shafeez">
  <img src="https://img.shields.io/badge/GitHub-mohamad--shafeez-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>

</div>

<br/>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="28"> &nbsp; About Me

Software Engineer focused on backend systems, AI runtimes, and real-time distributed applications.

I design and build backend platforms, AI infrastructure, developer tooling, and production-grade applications using Java, Spring Boot, Python, Node.js, Flask, React, Next.js, PostgreSQL, MongoDB, and modern AI/LLM technologies.

**Core Areas:**

- Backend Engineering & Scalable System Design
- AI Systems & Local LLM Infrastructure
- Real-Time Distributed Applications
- Event-Driven Architectures
- API Design & System Architecture
- DevOps Automation & Infrastructure Generation

I enjoy building systems that are fault-tolerant, event-driven, and optimized for real-world production use, especially where AI and backend engineering intersect.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<br/>

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> &nbsp; `Projects`

<br/>

### 🚀 &nbsp; AI DevOps Assistant &mdash; Automated Infrastructure Generation Platform

> *A full-stack platform that analyzes any codebase or GitHub repository and generates 12 production-ready DevOps artifacts — Dockerfiles, CI/CD pipelines, Kubernetes manifests, Terraform configs, and security audits — from a single structured Gemini AI prompt.*

![Java](https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white)
![SpringBoot](https://img.shields.io/badge/Spring_Boot_3.2-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![NextJS](https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL_16-336791?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_1.5%2F2.5_Flash-4285F4?style=flat-square&logo=google&logoColor=white)

<br/>

| 🏗️ Pillar | ⚙️ Implementation |
| :--- | :--- |
| **Single-Pass Generation** | One structured Gemini prompt synthesizes all 12 artifacts (Dockerfile, Compose, CI/CD, K8s, Helm, Terraform, security audit, code review, `.env.example`, deployment report, architecture docs, health scores) instead of 12 separate LLM calls |
| **Resilient AI Calls** | `GeminiApiService` — exponential backoff retry on HTTP 429/503, up to 4 attempts (2s → 4s → 8s), with graceful fallback error responses |
| **Repository Intelligence** | `GithubService` queries the GitHub Trees API (`/repos/{owner}/{repo}/git/trees`) to extract real repository structure and feed it into AI context |
| **Layered Spring Architecture** | Controller → Service → Repository → DTO, with Spring Data JPA persistence, Flyway-managed schema migrations, and global exception handling via `@RestControllerAdvice` |
| **Containerized Stack** | Docker Compose orchestrates PostgreSQL 16 + Spring Boot backend + Next.js frontend as a single-command deployment; Spring Actuator exposes a health endpoint for container probes |
| **Verified Test Suite** | JUnit 5 + MockMvc covering controller, service, and validation logic — 4/4 passing (focused baseline suite) |
| **Client Experience** | Next.js 14 App Router + TypeScript frontend — file tree viewer, syntax-highlighted code panels, 0–100 health/security score meters, one-click ZIP export via JSZip |

> ⚠️ **Note on generated artifacts:** the Kubernetes manifests, Helm charts, and Terraform configs are AI-synthesized *output* for a user's target codebase — the platform itself runs as a Docker Compose stack (Spring Boot + PostgreSQL + Next.js), not on Kubernetes.

<br/>

<a href="https://drive.google.com/file/d/1SVy8shQxEdl5-cUGS9U3uJmkA_4H1TXR/view?usp=sharing">
  <img src="https://img.shields.io/badge/%E2%96%B6%EF%B8%8F%20Video%20Walkthrough-Google%20Drive-FF0000?style=for-the-badge&logo=googledrive&logoColor=white&labelColor=0d1117"/>
</a>
&nbsp;
<a href="https://github.com/mohamad-shafeez/ai-devops-assistant">
  <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>

<br/><br/>

---

### ⚡ &nbsp; Cipher OS &mdash; Fault-Tolerant Local AI Runtime & OS Daemon

> *An experimental OS-level AI background daemon for Windows. Manages heavy multi-agent LLM workloads locally without ever blocking the primary voice interface or real-time audio streams.*

![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)
![Whisper](https://img.shields.io/badge/Faster--Whisper-00A67E?style=flat-square&logo=openai&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite_WAL-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma_VectorDB-7B2FBE?style=flat-square)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

<br/>

| 🏗️ Pillar | ⚙️ Implementation |
| :--- | :--- |
| **Process Isolation** | Heavy LLM tasks → `IDLE_PRIORITY_CLASS` subprocesses; Voice interface → `HIGH_PRIORITY_CLASS` — inference never blocks audio |
| **Dual Inference Lanes** | Separate local Ollama instances on ports `11434` (LiveTalk) and `11435` (Sovereign Mode) — bypasses query-queue bottlenecks |
| **Flatline Watchdog** | 3-second heartbeat pulses + 45-second deadlock detection → `SIGKILL` + auto-respawn with cooldown gate |
| **Three-Tier Memory** | Volatile working memory → SQLite WAL episodic store → Chroma semantic embeddings — auto-injected per inference call |
| **Agent Ecosystem** | **176 AI personas** across 13 domain directories in `agent_ecosystem/`, defined as individual prompt files; intent-based routing via `agent_router.py` |
| **Skill Architecture** | Modular plugin system using `importlib` with **startup-time discovery** across 10+ skill categories (vision, WhatsApp/Gmail automation, ADB Android control) — new skills load without touching core runtime code |
| **Evaluation Harness** | Hallucination, bias, and jailbreak benchmark suite with auto-generated PDF/MD reports |
| **IPC Layer** | Shared-nothing JSON `multiprocessing.Queue()` — no memory collision between parent/child processes on Windows `spawn` |
| **Safety Filters** | Runtime prompt injection detection and response filtering for jailbreak and toxic content |

<br/>

<a href="https://drive.google.com/file/d/15aT0SbL-bgEsEy-pLC1-Gyj09cFdAkgW/view?usp=sharing">
  <img src="https://img.shields.io/badge/%E2%96%B6%EF%B8%8F%20Video%20Walkthrough-Google%20Drive-FF0000?style=for-the-badge&logo=googledrive&logoColor=white&labelColor=0d1117"/>
</a>
&nbsp;
<a href="https://github.com/mohamad-shafeez/Cipher-AI">
  <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>

<br/><br/>

---

### 🗺️ &nbsp; SafeNav &mdash; AI-Powered Travel Safety Platform (Production PWA)

> *A full-stack health-aware route intelligence PWA. Synthesizes live weather, AQI, and traffic telemetry with Gemini AI to generate deterministic safety scores and health-personalized travel recommendations.*

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_1.5_Flash-8E44AD?style=flat-square&logo=google&logoColor=white)
![TomTom](https://img.shields.io/badge/TomTom_API-DF0A24?style=flat-square)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Fernet](https://img.shields.io/badge/Fernet_AES--128--CBC-00897B?style=flat-square)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)

<br/>

| 🏗️ Pillar | ⚙️ Implementation |
| :--- | :--- |
| **Deterministic Risk Engine** | Composite Safety Score (0–150) with adaptive health thresholds (31°C cardiac vs. 38°C standard) + non-linear exposure multiplier |
| **Dual-Route Intelligence** | TomTom bounding-box incident scanning (capped at 50) + Haversine geodesic math + fuel/CO₂/toll modeling |
| **AI Resilience** | Gemini exponential backoff on 429/503 responses; graceful degradation for all external APIs |
| **Secure Document Vault** | Fernet authenticated encryption (**AES-128-CBC + HMAC-SHA256**) + PyPDF2 text extraction + Gemini Vision AI for multimodal OCR/translation |
| **Admin Command Center** | JWT-verified kill-switch + immutable Firestore audit logs |
| **Production Stack** | Render (Gunicorn) backend + Vercel frontend, decoupled via a custom `vercel.json` proxy bridge; Stale-While-Revalidate PWA offline support |

<br/>

<a href="https://drive.google.com/file/d/1Bc9oYDfGGSERi5KU-XpOtrF12JbCOkti/view?usp=drive_link">
  <img src="https://img.shields.io/badge/%E2%96%B6%EF%B8%8F%20Video%20Walkthrough-Google%20Drive-FF0000?style=for-the-badge&logo=googledrive&logoColor=white&labelColor=0d1117"/>
</a>
&nbsp;
<a href="https://github.com/mohamad-shafeez/SafeNav">
  <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>

<br/><br/>

---

### 🔨 &nbsp; Auction House &mdash; Real-Time MERN Bidding Platform

> *High-fidelity live auction and token-draw platform. State-locked campaigns, WebSocket bid broadcasting, real-time grid locking, and a private user-admin chat system.*

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase_Auth-FFCA28?style=flat-square&logo=firebase&logoColor=black)

<br/>

- **3-Tier Listing System** — token-draw polls, live-bid auctions, and social posts under a unified Mongoose model
- **Real-Time WebSocket Layer** — Socket.io broadcasts bid updates and token grid locking to all clients instantly
- **Role-Based Access Control** — Admin, Seller, and User roles across 6+ Express route modules with JWT-protected endpoints
- **Cloudinary Integration** — image uploads for listings and seller-to-user chat, with consistent bid/chat history in MongoDB

<a href="https://github.com/mohamad-shafeez/Auction-House">
  <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>

<br/><br/>

---

### 🌐 &nbsp; EventEase &mdash; AI-Augmented Event Management Platform

> *Multi-role event platform. Flask + MySQL + Gemini AI managing event creation, booking, QR ticketing, and automated background tasks.*

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-8E44AD?style=flat-square&logo=google&logoColor=white)
![APScheduler](https://img.shields.io/badge/APScheduler-FF6F00?style=flat-square)

- **Gemini AI Toolkit** — assists with event descriptions and pricing suggestions
- **Booking Pipeline** — ticket booking, checkout, PDF/QR ticket generation, on-site check-in scanning
- **Background Automation** — APScheduler handles expired draft cleanup and status syncing
- **Role Dashboards** — creator, attendee, and admin views with RBAC-protected routes

<a href="https://github.com/mohamad-shafeez/EventEase">
  <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>

<br/><br/>

---

### 🗳️ &nbsp; VoteHub &mdash; Real-Time MERN Polling Platform

> *Secure voting application with JWT auth, role-based admin controls, and result visualizations.*

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

- JWT + bcrypt authentication with role-based admin controls
- Vote integrity enforced via compound unique index (`userId` + `pollId`) and MongoDB atomic operations preventing race conditions
- Poll deletion cascades to associated votes; live results visualization

<a href="https://github.com/mohamad-shafeez/VoteHub">
  <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<br/>

## 🛠️ &nbsp; `Technology Stack`

**Languages**
Java • Python • JavaScript • TypeScript • SQL

**Backend**
Spring Boot 3 • Spring Data JPA • Spring WebClient • Spring Actuator • Node.js • Express.js • Flask • REST APIs • Event-Driven Architecture • Multiprocessing

**AI & Automation**
Gemini API • Ollama • Faster-Whisper • Silero VAD • ChromaDB • Prompt Engineering • Semantic Search

**Frontend**
Next.js 14 • React • Tailwind CSS • PWA • Service Workers

**Databases**
PostgreSQL • MongoDB • MySQL • SQLite (WAL) • Firebase Firestore

**DevOps**
Docker • Docker Compose • Flyway • GitHub Actions • Maven

**Testing**
JUnit 5 • Mockito • MockMvc

**Real-Time Systems**
Socket.io • WebSockets

**Tools & Platforms**
Git • Postman • Cloudinary • Render • Vercel • Firebase • TomTom API • ADB

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<br/>

## 📬 &nbsp; `Contact`

<br/>

<div align="center">

<a href="mailto:shafeezchappi18@gmail.com">
  <img src="https://img.shields.io/badge/Email%20Me-shafeezchappi18%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/mohamad-shafeez">
  <img src="https://img.shields.io/badge/LinkedIn-mohamad--shafeez-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117"/>
</a>

<br/><br/>

> ### *Building backend systems, AI applications, developer tooling, and real-time platforms. Feel free to connect through LinkedIn or reach out by email.*

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,50:0a2a4a,100:020810&height=120&section=footer"/>

</div>
