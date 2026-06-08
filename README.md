# Hi, I'm Mohamad Shafeez 👋

### Systems & Backend Engineer specializing in Concurrent AI Runtimes and Real-Time Architectures

[![GitHub Stars](https://img.shields.io/github/stars/mohamad-shafeez?style=flat-square&color=FFD700)](https://github.com/mohamad-shafeez)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/mohamad-shafeez)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=flat-square&logo=gmail)](mailto:shafeezchappi18@gmail.com)

---

## 🧠 About Me
I design and build high-performance, fault-tolerant backend systems and local AI orchestration pipelines. My work focuses on solving complex engineering challenges like multi-process isolation, low-latency execution loops, real-time synchronization, and cryptographic data protection. I bridge systems engineering with LLM workflows, focusing on local, private, and deterministic AI execution.

---

## 🚀 Featured Projects

### ⚡ **[Cipher OS](https://github.com/mohamad-shafeez/Cipher-AI) — Concurrent Local AI Runtime**
A fault-tolerant background daemon and local AI runtime for Windows that manages heavy, multi-agent LLM workloads locally without blocking user interfaces or real-time audio streams.

*   **Systems Architecture**: Multi-process worker sandboxing utilizing standard `multiprocessing` spawn protocols to enforce strict process isolation and prevent memory or execution leakage.
*   **CPU Priority Scheduling**: Implements dual cognitive paths, prioritizing LiveTalk audio threads (`HIGH_PRIORITY_CLASS`) over heavy reasoning swarms (`IDLE_PRIORITY_CLASS`) to eliminate VAD audio preemption.
*   **Kernel Watchdog & Recovery**: Integrates a supervision loop tracking process heartbeats with automated native crash recovery (SIGKILL/force-terminations) and respawn cooldown gates.
*   **Memory Eviction & WAL**: Optimizes local hardware utilization via active GPU VRAM eviction routines and SQLite Write-Ahead Logging (WAL) for lock-free database writes.
*   **Tech Stack**: `Python`, `Ollama API (Qwen / Moondream)`, `Faster-Whisper`, `Silero VAD`, `SQLite (WAL)`, `WebSockets (HUD Telemetry)`
*   **Walkthrough**: [Watch Demo Video](https://drive.google.com/file/d/15aT0SbL-bgEsEy-pLC1-Gyj09cFdAkgW/view?usp=sharing)

---

### 🗺️ **[SafeNav](https://github.com/mohamad-shafeez/SafeNav) — AI-Powered Travel Safety Engine**
A health-aware route optimization platform that synthesizes live environmental telemetry (weather, AQI, traffic incident details) with AI model analysis to calculate personalized risk metrics.

*   **Route Optimization Engine**: Leverages TomTom APIs to extract real-time incidents and traffic delays, executing server-side geodesic coordinate mathematics to compute custom safety paths.
*   **Deterministic Risk Framework**: Processes raw environmental telemetry via rule-based mathematical heuristics combined with Google Gemini LLM generation.
*   **AI Resilience (Retry Shield)**: Implements an automated API key rotation scheme and exponential backoff retry mechanism to prevent runtime failures during API throttling.
*   **Multi-Tier Vault Security**: Integrates a secure document lifecycle using Fernet AES-256-CBC encryption, PBKDF2-HMAC-SHA256 key derivation, and SHA-256 file integrity checksums.
*   **Tech Stack**: `Python Flask`, `Vanilla JS`, `Gemini API`, `TomTom API`, `Firebase`, `Progressive Web App (PWA)`
*   **Walkthrough**: [Watch Demo Video](https://drive.google.com/file/d/1Bc9oYDfGGSERi5KU-XpOtrF12JbCOkti/view?usp=drive_link)

---

### 🔨 **[Auction House](https://github.com/mohamad-shafeez/Auctin-House) — Real-Time Bidding & Campaign Platform**
A high-fidelity live bidding and raffle-based token draw platform designed to orchestrate state-locked campaigns and real-time user-merchant interactions.

*   **Real-Time Synchronization**: Built on a Node.js/Express WebSocket layer using Socket.io to stream real-time bid updates, chat attachments, and immediate numeric draw-grid locking.
*   **RBAC & Security**: Protects transactional endpoints with Role-Based Access Control and Firebase token authentication.
*   **Media Ingestion**: Features an asynchronous Multer and Cloudinary integration for handling client-side image uploads and real-time media transformations.
*   **Tech Stack**: `MongoDB`, `Express.js`, `React`, `Node.js (MERN)`, `Socket.io`, `Firebase Auth`, `Cloudinary`

---

## 🛠️ Skills Snapshot

| Category | Technologies |
| :--- | :--- |
| **Languages** | Python, JavaScript (ES6+), SQL (MySQL, SQLite), HTML5, CSS3 |
| **Backend & Systems** | Node.js, Express.js, Flask, REST APIs, Multiprocessing, Concurrency, Event-Driven Architecture |
| **AI Orchestration** | Local LLM Systems, Ollama, Whisper STT, Silero VAD, Prompt Engineering, Semantic Vector Memory |
| **Real-Time & Security** | WebSockets (Socket.io), Server-Sent Events, JWT, Cryptography (AES-256, Fernet, PBKDF2), RBAC |
| **Databases** | MongoDB, Firebase Firestore, MySQL, SQLite (WAL mode) |
| **Tools & Hosting** | Git, Postman, Cloudinary, Vercel, Netlify, Render, MapLibre GL, TomTom API, Android ADB |

---

## 📫 Connect With Me
*   **Email**: shafeezchappi18@gmail.com
*   **LinkedIn**: [linkedin.com/in/mohamad-shafeez](https://linkedin.com/in/mohamad-shafeez)
*   **Live Portfolios**: [Cipher AI](https://cipher-voice-ai.netlify.app) · [SafeNav](https://safe-nav-pied.vercel.app/)
