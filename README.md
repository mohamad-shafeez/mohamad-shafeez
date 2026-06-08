cat > /mnt/user-data/outputs/README.md << 'MDEOF'
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:020810,40:051528,100:0a2a4a&height=200&section=header&text=Mohamad%20Shafeez&fontSize=56&fontColor=ffffff&fontAlignY=42&desc=Backend%20Engineer%20%E2%80%A2%20AI%20Systems%20%E2%80%A2%20Real-Time%20Architectures&descAlignY=62&descSize=16&descColor=90caf9"/>

<br/>

<a href="https://linkedin.com/in/mohamad-shafeez">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:shafeezchappi18@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://github.com/mohamad-shafeez">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

<br/>

---

## About

```python
class MohamadShafeez:

    role        = "Backend Engineer & AI Systems Builder"
    university  = "Srinivas University, Mangalore  —  BCA, Graduating May 2026"
    location    = "Mangalore, India"

    focus  = [
        "Fault-tolerant concurrent AI runtimes & OS-level daemons",
        "High-throughput backend APIs & real-time event-driven systems",
        "Local LLM orchestration & multi-agent AI architectures",
        "Cryptographic security, deterministic risk engines & PWA deployment",
    ]

    contact  = "shafeezchappi18@gmail.com"
```

---

## Projects

<br/>

### Cipher OS &nbsp;—&nbsp; Local AI Runtime & OS Daemon

> An OS-level AI background daemon for Windows. Manages heavy multi-agent LLM workloads locally without blocking the primary voice interface or real-time audio streams.

![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![Whisper](https://img.shields.io/badge/Faster--Whisper-00A67E?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite_WAL-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma_VectorDB-7B2FBE?style=flat-square)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

| Pillar | Implementation |
| :--- | :--- |
| **Process Isolation** | Heavy LLM tasks run in `IDLE_PRIORITY_CLASS` subprocesses; voice interface locked to `HIGH_PRIORITY_CLASS` — inference never blocks audio |
| **Dual Inference Lanes** | Separate Ollama instances on ports `11434` (fast path) and `11435` (heavy compute) bypass query-queue bottlenecks |
| **Watchdog & Recovery** | 3-second heartbeat pulses + 45-second deadlock detection → `SIGKILL` + auto-respawn with cooldown gate — zero main-thread crashes |
| **Three-Tier Memory** | Volatile working memory → SQLite WAL episodic store → Chroma semantic embeddings, auto-injected per inference call |
| **Agent System** | 150+ AI personas across 13 domains; intent-based routing; 58+ modular skill plugins with dynamic hot-reload |
| **Evaluation Harness** | Hallucination, bias, jailbreak & model comparison benchmark suite — auto-generates PDF/Markdown reports |
| **VRAM Management** | Active GPU eviction (`keep_alive: 0`) + `gc.collect()` post-task to prevent RAM/VRAM exhaustion |
| **IPC Layer** | Shared-nothing JSON `multiprocessing.Queue()` — no memory collision between parent/child processes on Windows `spawn` |

<a href="https://drive.google.com/file/d/15aT0SbL-bgEsEy-pLC1-Gyj09cFdAkgW/view?usp=sharing">
  <img src="https://img.shields.io/badge/Video%20Walkthrough-Google%20Drive-FF0000?style=for-the-badge&logo=googledrive&logoColor=white"/>
</a>
&nbsp;
<a href="https://github.com/mohamad-shafeez/Cipher-AI">
  <img src="https://img.shields.io/badge/Source%20Code-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

---

### SafeNav &nbsp;—&nbsp; AI-Powered Travel Safety Platform

> A full-stack health-aware route intelligence PWA. Synthesizes live weather, AQI, and traffic telemetry with Gemini AI to generate deterministic safety scores and health-personalized travel recommendations.

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_1.5_Flash-8E44AD?style=flat-square&logo=google&logoColor=white)
![TomTom](https://img.shields.io/badge/TomTom_API-DF0A24?style=flat-square)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![AES256](https://img.shields.io/badge/AES--256_Fernet-00897B?style=flat-square)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square)

| Pillar | Implementation |
| :--- | :--- |
| **Risk Engine** | Composite Safety Score (0–150) with adaptive health thresholds (31°C cardiac vs. 38°C standard) and non-linear exposure multiplier |
| **Dual-Route System** | TomTom BBox incident scanning + Haversine geodesic math + fuel/CO₂/toll modeling — fastest vs. health-optimized path |
| **AI Resilience** | Gemini exponential backoff + API key rotation on 429/503; graceful degradation across all external APIs |
| **Document Vault** | 22 document types — Fernet AES-256-CBC + PBKDF2-HMAC-SHA256 key derivation + SHA-256 checksums + Gemini Vision validation |
| **Admin Panel** | JWT-verified kill-switch (L0–L3 threat levels), immutable Firestore audit logs, real-time API quota monitoring |
| **Deployment** | Render (Gunicorn) + Firebase Hosting + Vercel fallback — Stale-While-Revalidate Service Worker for offline PWA |

<a href="https://drive.google.com/file/d/1Bc9oYDfGGSERi5KU-XpOtrF12JbCOkti/view?usp=drive_link">
  <img src="https://img.shields.io/badge/Video%20Walkthrough-Google%20Drive-FF0000?style=for-the-badge&logo=googledrive&logoColor=white"/>
</a>
&nbsp;
<a href="https://github.com/mohamad-shafeez/SafeNav">
  <img src="https://img.shields.io/badge/Source%20Code-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

---

### Auction House &nbsp;—&nbsp; Real-Time MERN Bidding Platform

> High-fidelity live auction and token-draw platform. State-locked campaigns, WebSocket bid broadcasting, real-time grid locking, and a private user-admin chat system.

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React_v19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square)

- **Hybrid Listing Engine** — DRAW (100-slot token grid), LIVE_BID (real-time auction rooms), and SOCIAL campaign types under a unified Mongoose model
- **Real-Time Layer** — Socket.io broadcasts bid updates, emoji reactions, and token grid locking instantly across all connected clients
- **State Integrity** — Token locking on purchase prevents double-booking; MongoDB TTL index auto-expires campaigns 2 days post end-time
- **Admin Controls** — User management with ban/unban, campaign creation with Cloudinary media upload, real-time chat inbox

<a href="https://github.com/mohamad-shafeez/Auctin-House">
  <img src="https://img.shields.io/badge/Source%20Code-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

---

### EventEase &nbsp;—&nbsp; Multi-Role Event Management Platform

> Production-ready event platform built with Flask, MySQL, and Gemini AI. Manages the full event lifecycle across creators, attendees, and administrators.

![Flask](https://img.shields.io/badge/Flask_3.1-000000?style=flat-square&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-8E44AD?style=flat-square&logo=google&logoColor=white)
![APScheduler](https://img.shields.io/badge/APScheduler-FF6F00?style=flat-square)

- **Gemini AI Toolkit** — Auto-generates event descriptions, INR pricing with local market reasoning, and WhatsApp promotional copy
- **Booking Pipeline** — Ticket booking → checkout → PDF/QR code ticket generation → on-site check-in scanning
- **Background Automation** — APScheduler cancels expired drafts, promotes waitlists, and syncs event statuses without manual intervention
- **Role Dashboards** — Creator analytics (revenue, fill rates), attendee bookmarks/reviews, admin moderation with AI content flagging

<a href="https://github.com/mohamad-shafeez/EventEase">
  <img src="https://img.shields.io/badge/Source%20Code-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

---

### VoteHub &nbsp;—&nbsp; Real-Time MERN Polling Platform

> Secure voting application with JWT authentication, role-based admin controls, Chart.js result visualizations, and live platform settings — no redeployment required.

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![ChartJS](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

- JWT + bcrypt authentication; first registered user is automatically assigned Admin role
- Admin system settings: toggle registration, open/close voting, update site name — all applied live
- Poll deletion cascades to all associated votes; Chart.js visualizations for real-time results

<a href="https://github.com/mohamad-shafeez/VoteHub">
  <img src="https://img.shields.io/badge/Source%20Code-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/>

---

## Tech Stack

```json
{
  "languages"  :  ["Python", "JavaScript (ES6+)", "HTML5", "CSS3", "SQL"],

  "backend"    :  {
    "frameworks":  ["Node.js", "Express.js", "Flask"],
    "patterns"  :  ["REST APIs", "Event-Driven Architecture", "Multiprocessing",
                    "IPC (JSON Lines)", "CPU Priority Scheduling", "WAL Mode SQLite"],
    "security"  :  ["JWT", "RBAC", "AES-256 / Fernet", "PBKDF2-HMAC-SHA256",
                    "Firebase Auth", "bcrypt"]
  },

  "ai_ml"      :  {
    "inference" :  ["Ollama", "Gemini 1.5 Flash", "Faster-Whisper STT", "Silero VAD"],
    "memory"    :  ["Chroma Vector DB", "SQLite WAL", "Semantic Embeddings"],
    "patterns"  :  ["RAG", "Prompt Engineering", "Multi-Agent Orchestration",
                    "Tool-Use Agents", "Hallucination Detection", "Safety Filtering"]
  },

  "frontend"   :  ["React.js", "Next.js 14", "Tailwind CSS", "Framer Motion",
                   "Vanilla JavaScript", "PWA", "Service Workers", "MapLibre GL JS"],

  "databases"  :  ["MongoDB", "Firebase Firestore", "SQLite", "MySQL"],

  "realtime"   :  ["Socket.io", "WebSockets", "Server-Sent Events (SSE)"],

  "devops"     :  ["Git", "Gunicorn", "Render", "Vercel", "Firebase Hosting",
                   "Postman", "Cloudinary", "TomTom API", "ADB"]
}
```

---

## GitHub Stats

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=mohamad-shafeez&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=90caf9&icon_color=90caf9&text_color=c9d1d9&ring_color=1565c0&count_private=true"/>
&nbsp;&nbsp;
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohamad-shafeez&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=90caf9&text_color=c9d1d9&langs_count=8"/>

<br/><br/>

<img width="65%" src="https://github-readme-streak-stats.herokuapp.com/?user=mohamad-shafeez&theme=github-dark-blue&hide_border=true&background=0d1117&ring=1565c0&fire=90caf9&currStreakLabel=90caf9"/>

</div>

---

## Contact

<div align="center">

<a href="mailto:shafeezchappi18@gmail.com">
  <img src="https://img.shields.io/badge/shafeezchappi18%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/mohamad-shafeez">
  <img src="https://img.shields.io/badge/linkedin.com%2Fin%2Fmohamad--shafeez-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a2a4a,100:020810&height=100&section=footer"/>

</div>
MDEOF
echo "Done"
Output

Done
Done

You are out of free messages until 6:00 PM
Upgrade
