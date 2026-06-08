<div align="center">

<!-- HEADER BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0d2137,100:00b4d8&height=180&section=header&text=Mohamad%20Shafeez&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Backend%20Engineer%20%7C%20AI%20Systems%20%7C%20Real-Time%20Architectures&descAlignY=60&descSize=16&descColor=7dd3fc" />

<!-- STATUS BADGES -->
<p>
  <img src="https://img.shields.io/badge/Status-Open%20to%20Internships-00d26a?style=for-the-badge&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Location-Mangalore%2C%20India-00b4d8?style=for-the-badge&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Focus-Backend%20%7C%20AI%20%7C%20Full--Stack-7dd3fc?style=for-the-badge&labelColor=0d1117" />
</p>

<!-- SOCIAL LINKS -->
<p>
  <a href="https://linkedin.com/in/mohamad-shafeez">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:shafeezchappi18@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://safe-nav-pied.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Project-SafeNav-00b4d8?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://cipher-voice-ai.netlify.app">
    <img src="https://img.shields.io/badge/Live%20Project-Cipher%20AI-7dd3fc?style=for-the-badge&logo=netlify&logoColor=white" />
  </a>
</p>

</div>

---

## `> whoami`

```python
class MohamadShafeez:

    role        = "Backend Engineer & AI Systems Builder"
    university  = "Srinivas University, Mangalore — BCA, Graduating May 2026"
    location    = "Mangalore, India  →  targeting Bangalore / Remote"

    specialization = [
        "Fault-tolerant concurrent AI runtimes",
        "High-throughput backend APIs & real-time systems",
        "Local LLM orchestration & multi-agent architectures",
        "Cryptographic security & production PWA deployment",
    ]

    currently_building = "Cipher OS — an offline-first multi-agent AI operating daemon"
    open_to            = "Backend · Full-Stack · AI/ML Internships (2026)"
    contact            = "shafeezchappi18@gmail.com"
```

---

## `> ls ./projects --flagship`

<br/>

### ⚡ Cipher OS — Fault-Tolerant Local AI Runtime

> *An experimental OS-level AI background daemon for Windows. Manages heavy multi-agent LLM workloads locally without ever blocking the primary voice interface or real-time audio streams.*

<p>
  <img src="https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Faster--Whisper-00A67E?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Silero_VAD-FF6F00?style=flat-square"/>
  <img src="https://img.shields.io/badge/SQLite_WAL-003B57?style=flat-square&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Chroma_VectorDB-7B2FBE?style=flat-square"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
</p>

| Engineering Pillar | Implementation |
| :--- | :--- |
| **Process Isolation** | Heavy LLM tasks run in `IDLE_PRIORITY_CLASS` subprocesses; voice interface locked to `HIGH_PRIORITY_CLASS` — inference never blocks audio |
| **Dual Inference Lanes** | Separate Ollama instances on ports 11434 (LiveTalk) and 11435 (Sovereign Mode) bypass query-queue bottlenecks |
| **Flatline Watchdog** | 3-second heartbeat pulses + 45-second deadlock detection → SIGKILL + auto-respawn with cooldown gate |
| **Three-Tier Memory** | Volatile working memory → SQLite WAL episodic store → Chroma semantic embeddings, auto-injected per inference call |
| **Agent Ecosystem** | 150+ AI personas across 13 domains; intent-based routing via `agent_router.py` |
| **Skill Architecture** | 58+ modular plugins (vision, WhatsApp/Gmail automation, ADB Android control) with dynamic hot-reload |
| **Evaluation Harness** | Production-grade hallucination, bias, jailbreak & OSS-vs-frontier benchmark suite → auto-generated PDF/MD reports |
| **VRAM Management** | Active GPU eviction (`keep_alive: 0`) + Python `gc.collect()` post-task to prevent RAM/VRAM exhaustion |

<p>
  <a href="https://drive.google.com/file/d/15aT0SbL-bgEsEy-pLC1-Gyj09cFdAkgW/view?usp=sharing">
    <img src="https://img.shields.io/badge/▶_Video_Walkthrough-Drive-FF0000?style=for-the-badge&logo=googledrive&logoColor=white"/>
  </a>
  <a href="https://github.com/mohamad-shafeez/Cipher-AI">
    <img src="https://img.shields.io/badge/Source_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://cipher-voice-ai.netlify.app">
    <img src="https://img.shields.io/badge/Live_Demo-Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white"/>
  </a>
</p>

---

### 🗺️ SafeNav — AI-Powered Travel Safety Platform

> *A full-stack, health-aware route intelligence PWA. Synthesizes live weather, AQI, and traffic telemetry with Gemini AI to generate deterministic safety scores and health-personalized travel recommendations.*

<p>
  <img src="https://img.shields.io/badge/Python_Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini_1.5_Flash-8E44AD?style=flat-square&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/TomTom_API-DF0A24?style=flat-square"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/AES--256_Fernet-00897B?style=flat-square"/>
  <img src="https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white"/>
  <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black"/>
</p>

| Engineering Pillar | Implementation |
| :--- | :--- |
| **Deterministic Risk Engine** | Composite Safety Score (0–150) with adaptive health-profile thresholds (31°C cardiac vs. 38°C standard) and non-linear exposure multiplier |
| **Dual-Route Intelligence** | TomTom real-time incident scanning via BBox, Haversine geodesic math, fuel/CO₂/toll cost modeling — fastest vs. safest path comparison |
| **AI Resilience** | Gemini exponential backoff + API key rotation on 429/503; graceful degradation for all external APIs |
| **Secure Document Vault** | 22 document types — Fernet AES-256-CBC + PBKDF2-HMAC-SHA256 key derivation + SHA-256 integrity checksums + Gemini Vision validation |
| **Admin Command Center** | JWT-verified kill-switch (L0–L3 threat levels), immutable Firestore audit logs, real-time API quota monitoring |
| **Production Deployment** | Render (Gunicorn) + Firebase Hosting + Vercel serverless fallback — Stale-While-Revalidate PWA offline support |

<p>
  <a href="https://drive.google.com/file/d/1Bc9oYDfGGSERi5KU-XpOtrF12JbCOkti/view?usp=drive_link">
    <img src="https://img.shields.io/badge/▶_Video_Walkthrough-Drive-FF0000?style=for-the-badge&logo=googledrive&logoColor=white"/>
  </a>
  <a href="https://github.com/mohamad-shafeez/SafeNav">
    <img src="https://img.shields.io/badge/Source_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://safe-nav-pied.vercel.app/">
    <img src="https://img.shields.io/badge/Live_Demo-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
</p>

---

### 🔨 Auction House — Real-Time MERN Bidding Platform

> *A high-fidelity live auction and token-draw platform. Manages state-locked campaigns, real-time bidding, and user-merchant interactions with a hybrid 3-tier listing system.*

<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/React_v19-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase_Auth-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square"/>
</p>

- **Hybrid Listing Engine** — DRAW (100-slot token grid), BID/LIVE_BID (real-time auction rooms), and SOCIAL (post) campaign types under a unified Mongoose model
- **Real-Time WebSocket Layer** — Socket.io broadcasts bid updates, emoji reactions, grid locking, and presence notifications to all connected clients instantly
- **State-Locked Grid** — Token number locking on purchase prevents double-booking; MongoDB TTL index auto-expires campaigns 2 days after `endTime`
- **Admin God Mode** — User management with ban/unban, campaign creation, real-time chat inbox, and Cloudinary media ingestion via Multer

<p>
  <a href="https://github.com/mohamad-shafeez/Auctin-House">
    <img src="https://img.shields.io/badge/Source_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

### 🌐 EventEase — AI-Augmented Event Management Platform

> *A production-ready multi-role event platform powered by Flask, MySQL, and Gemini AI. Manages the full event lifecycle across creators, attendees, and administrators.*

<p>
  <img src="https://img.shields.io/badge/Flask_3.1-000000?style=flat-square&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini_AI-8E44AD?style=flat-square&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/APScheduler-FF6F00?style=flat-square"/>
  <img src="https://img.shields.io/badge/QR_Codes-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
</p>

- **Gemini AI Toolkit** — Auto-generates 150-word event descriptions, INR pricing recommendations with local market reasoning, and WhatsApp social media copy
- **Full Booking Pipeline** — Ticket booking → simulated checkout → PDF/QR code ticket generation → check-in scanning
- **Background Automation** — APScheduler cancels expired drafts, promotes waitlists, and updates event statuses automatically
- **Role-Based Dashboards** — Separate creator analytics (revenue, fill rates), attendee profiles, and admin moderation panel with AI content flagging

<p>
  <a href="https://github.com/mohamad-shafeez/EventEase">
    <img src="https://img.shields.io/badge/Source_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

### 🗳️ VoteHub — Real-Time Polling Platform

> *A secure MERN-stack voting application with role-based authorization, real-time poll management, and interactive data visualizations.*

<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
</p>

- JWT authentication with bcrypt hashing; first-registered user auto-assigned Admin role
- Admin system settings: real-time toggles for registration, platform-wide voting, and site name — no redeploy needed
- Chart.js visualizations for poll results; MongoDB TTL-style cleanup on poll deletion cascades to all associated votes

<p>
  <a href="https://github.com/mohamad-shafeez/VoteHub">
    <img src="https://img.shields.io/badge/Source_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## `> cat ./tech_stack.json`

```json
{
  "languages":      ["Python", "JavaScript (ES6+)", "HTML5", "CSS3", "SQL"],

  "backend": {
    "frameworks":   ["Node.js", "Express.js", "Flask"],
    "patterns":     ["REST APIs", "Event-Driven Architecture", "Multiprocessing",
                     "IPC (JSON Lines)", "CPU Priority Scheduling", "WAL Mode SQLite"],
    "security":     ["JWT", "RBAC", "AES-256 / Fernet", "PBKDF2-HMAC-SHA256",
                     "Firebase Auth", "bcrypt"]
  },

  "ai_ml": {
    "inference":    ["Ollama", "Gemini 1.5 Flash", "Faster-Whisper STT", "Silero VAD"],
    "memory":       ["Chroma Vector DB", "SQLite WAL", "Semantic Embeddings"],
    "patterns":     ["RAG", "Prompt Engineering", "Multi-Agent Orchestration",
                     "Tool-Use Agents", "Hallucination Detection", "Safety Filtering"]
  },

  "frontend":       ["React.js", "Next.js 14", "Tailwind CSS", "Framer Motion",
                     "Vanilla JavaScript", "PWA", "Service Workers", "MapLibre GL JS"],

  "databases":      ["MongoDB", "Firebase Firestore", "SQLite", "MySQL"],

  "realtime":       ["Socket.io", "WebSockets", "Server-Sent Events (SSE)"],

  "devops_tools":   ["Git", "Gunicorn", "Render", "Vercel", "Firebase Hosting",
                     "Netlify", "Postman", "Cloudinary", "TomTom API", "ADB"]
}
```

---

## `> ./stats --github`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=mohamad-shafeez&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&icon_color=7dd3fc&text_color=c9d1d9&ring_color=00b4d8" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohamad-shafeez&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&text_color=c9d1d9&langs_count=8" />

</div>

---

## `> cat ./contact.txt`

<div align="center">

| Channel | Link |
| :---: | :---: |
| 📧 Email | [shafeezchappi18@gmail.com](mailto:shafeezchappi18@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/mohamad-shafeez](https://linkedin.com/in/mohamad-shafeez) |
| 🌐 SafeNav Live | [safe-nav-pied.vercel.app](https://safe-nav-pied.vercel.app/) |
| ⚡ Cipher Live | [cipher-voice-ai.netlify.app](https://cipher-voice-ai.netlify.app) |

<br/>

> *I'm actively seeking backend, full-stack, or AI/ML internship roles for 2026.*
> *If you're building something ambitious — I'd love to talk.*

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,50:0d2137,100:0d1117&height=100&section=footer" />

</div>
