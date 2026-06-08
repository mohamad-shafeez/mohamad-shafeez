# Hi, I'm Mohamad Shafeez 👋

<p align="left">
  <a href="https://linkedin.com/in/mohamad-shafeez" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:shafeezchappi18@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/mohamad-shafeez">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

### 🚀 Systems & Backend Engineer
Specializing in **Concurrent Local AI Runtimes**, **High-Throughput Backend APIs**, and **Real-Time Event-Driven Architectures**.

---

## 🧠 About Me

I design and build high-performance, fault-tolerant backend systems and local AI orchestration pipelines. My work focuses on solving complex engineering problems like **multi-process isolation**, **low-latency execution loops**, **real-time synchronization**, and **cryptographic data protection**. I bridge systems engineering with LLM workflows, focusing on local, private, and deterministic AI execution.

* 🔭 Currently focusing on **local multi-agent systems and fault-tolerant background runtimes**.
* ⚡ Core focus: **Maximizing hardware efficiency (VRAM/RAM) and ensuring thread responsiveness in hybrid systems**.

---

## 🛠️ Tech Stack & Capabilities

| Category | Technologies |
| :--- | :--- |
| **Languages** | `Python` · `JavaScript (ES6+)` · `SQL` · `HTML5/CSS3` |
| **Backend & Systems** | `Node.js` · `Express.js` · `Flask` · `Multiprocessing` · `CPU Scheduling` · `IPC (JSON Lines)` |
| **AI Orchestration** | `Ollama` · `Faster-Whisper STT` · `Silero VAD` · `Vector Memory (Chroma)` · `Prompt Engineering` |
| **Real-Time & Security** | `Socket.io` · `Server-Sent Events (SSE)` · `JWT` · `Fernet (AES-256)` · `PBKDF2` · `RBAC` |
| **Databases** | `MongoDB` · `Firebase Firestore` · `SQLite (WAL Mode)` · `MySQL` |
| **Developer Tools** | `Git` · `Postman` · `Cloudinary` · `Docker (basic)` · `Vercel` · `Render` · `Android ADB` |

---

## 🚀 Featured Flagship Projects

### ⚡ **Cipher OS — Concurrent Local AI Runtime**
*A fault-tolerant background daemon and local AI runtime for Windows that manages heavy, multi-agent LLM workloads locally without blocking user interfaces or real-time audio streams.*

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/Whisper_STT-00A67E?style=flat-square&logo=openai&logoColor=white" alt="Whisper" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Windows_Kernel-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows" />
</p>

*   **Systems Architecture**: Multi-process worker sandboxing utilizing standard `multiprocessing` spawn protocols to enforce strict process isolation and prevent memory or execution leakage.
*   **CPU Priority Scheduling**: Implements dual cognitive paths, prioritizing LiveTalk audio threads (`HIGH_PRIORITY_CLASS`) over heavy reasoning swarms (`IDLE_PRIORITY_CLASS`) to eliminate VAD audio preemption.
*   **Kernel Watchdog & Recovery**: Integrates a supervision loop tracking process heartbeats with automated native crash recovery (SIGKILL/force-terminations) and respawn cooldown gates.
*   **Memory Eviction & WAL**: Optimizes local hardware utilization via active GPU VRAM eviction routines and SQLite Write-Ahead Logging (WAL) for lock-free database writes.
*   **Demo & Code**: 🎥 [Google Drive Walkthrough](https://drive.google.com/file/d/15aT0SbL-bgEsEy-pLC1-Gyj09cFdAkgW/view?usp=sharing) | 💻 [GitHub Repo](https://github.com/mohamad-shafeez/Cipher-AI)

---

### 🗺️ **SafeNav — AI-Powered Travel Safety Engine**
*A health-aware route optimization platform that synthesizes live environmental telemetry (weather, AQI, traffic incident details) with AI model analysis to calculate personalized risk metrics.*

<p align="left">
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JS" />
  <img src="https://img.shields.io/badge/Gemini_AI-8E44AD?style=flat-square&logo=google-gemini&logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/TomTom_API-DF0A24?style=flat-square&logo=tomtom&logoColor=white" alt="TomTom" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white" alt="PWA" />
</p>

*   **Route Optimization Engine**: Leverages TomTom APIs to extract real-time incidents and traffic delays, executing server-side geodesic coordinate mathematics to compute custom safety paths.
*   **Deterministic Risk Framework**: Processes raw environmental telemetry via rule-based mathematical heuristics combined with Google Gemini LLM generation.
*   **AI Resilience (Retry Shield)**: Implements an automated API key rotation scheme and exponential backoff retry mechanism to prevent runtime failures during API throttling.
*   **Multi-Tier Vault Security**: Integrates a secure document lifecycle using Fernet AES-256-CBC encryption, PBKDF2-HMAC-SHA256 key derivation, and SHA-256 file integrity checksums.
*   **Demo & Code**: 🎥 [Google Drive Walkthrough](https://drive.google.com/file/d/1Bc9oYDfGGSERi5KU-XpOtrF12JbCOkti/view?usp=drive_link) | 💻 [GitHub Repo](https://github.com/mohamad-shafeez/SafeNav)

---

### 🔨 **Auction House — Real-Time Bidding & Campaign Platform**
*A high-fidelity live bidding and raffle-based token draw platform designed to orchestrate state-locked campaigns and real-time user-merchant interactions.*

<p align="left">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.io" />
  <img src="https://img.shields.io/badge/Cloudinary-34495E?style=flat-square&logo=cloudinary&logoColor=white" alt="Cloudinary" />
</p>

*   **Real-Time Synchronization**: Built on a Node.js/Express WebSocket layer using Socket.io to stream real-time bid updates, chat attachments, and immediate numeric draw-grid locking.
*   **RBAC & Security**: Protects transactional endpoints with Role-Based Access Control and Firebase token authentication.
*   **Media Ingestion**: Features an asynchronous Multer and Cloudinary integration for handling client-side image uploads and real-time media transformations.
*   **Code**: 💻 [GitHub Repo](https://github.com/mohamad-shafeez/Auctin-House)

---

## 📫 Connect & Collaborate

*   **Email**: [shafeezchappi18@gmail.com](mailto:shafeezchappi18@gmail.com)
*   **LinkedIn**: [linkedin.com/in/mohamad-shafeez](https://linkedin.com/in/mohamad-shafeez)
