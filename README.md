<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:020810,30:051528,70:0a2a4a,100:00b4d8&height=220&section=header&text=Mohamad%20Shafeez&fontSize=58&fontColor=ffffff&fontAlignY=40&fontAlign=50&desc=Backend%20Engineer%20%E2%80%A2%20AI%20Systems%20%E2%80%A2%20Real-Time%20Architectures&descAlignY=62&descSize=17&descColor=7dd3fc&animation=fadeIn" />

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=800&color=00B4D8&center=true&vCenter=true&multiline=false&width=700&lines=Building+fault-tolerant+AI+runtimes+%F0%9F%A4%96;Architecting+real-time+backend+systems+%E2%9A%A1;Orchestrating+local+multi-agent+LLM+workflows+%F0%9F%A7%A0;Open+to+Backend+%7C+Full-Stack+%7C+AI%2FML+Internships+%F0%9F%9A%80)](https://git.io/typing-svg)

</div>

<br/>

<div align="center">

![Status](https://img.shields.io/badge/%F0%9F%9F%A2%20Status-Open%20to%20Internships%202026-00d26a?style=for-the-badge&labelColor=0d1117&color=00d26a)
&nbsp;
![Location](https://img.shields.io/badge/%F0%9F%93%8D%20Mangalore%2C%20India-%E2%86%92%20Bangalore%20%2F%20Remote-00b4d8?style=for-the-badge&labelColor=0d1117&color=00b4d8)
&nbsp;
![BCA](https://img.shields.io/badge/%F0%9F%8E%93%20BCA-Graduating%20May%202026-7dd3fc?style=for-the-badge&labelColor=0d1117&color=7dd3fc)

<br/><br/>

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

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="28"> &nbsp; `About Me`

```python
class MohamadShafeez:

    role        = "Backend Engineer & AI Systems Builder"
    university  = "Srinivas University, Mangalore  —  BCA, Graduating May 2026"
    location    = "Mangalore, India  →  Targeting Bangalore / Remote"

    core_focus  = [
        "Fault-tolerant concurrent AI runtimes & OS-level daemons",
        "High-throughput backend APIs & real-time event-driven systems",
        "Local LLM orchestration & multi-agent AI architectures",
        "Cryptographic security, deterministic risk engines & PWA deployment",
    ]

    flagship    = "Cipher OS  —  an offline-first multi-agent AI operating daemon"
    seeking     = "Backend · Full-Stack · AI/ML  Internships  (2026)"
    contact     = "shafeezchappi18@gmail.com"

    def __init__(self):
        self.coffee_dependent = True
        self.ships_production_code = True
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<br/>

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> &nbsp; `## Projects`

<br/>

### ⚡ &nbsp; Cipher OS &mdash; Fault-Tolerant Local AI Runtime & OS Daemon

<img align="right" width="38%" src="https://github-readme-stats.vercel.app/api/pin/?username=mohamad-shafeez&repo=Cipher-AI&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&icon_color=7dd3fc&text_color=8b949e"/>

> *An experimental OS-level AI background daemon for Windows. Manages heavy multi-agent LLM workloads locally without ever blocking the primary voice interface or real-time audio streams.*

![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)
![Whisper](https://img.shields.io/badge/Faster--Whisper-00A67E?style=flat-square&logo=openai&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite_WAL-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma_VectorDB-7B2FBE?style=flat-square)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

<br clear="right"/>

<details>
<summary><b>🔬 &nbsp; Engineering Architecture — Click to Expand</b></summary>

<br/>

| 🏗️ Pillar | ⚙️ Implementation |
| :--- | :--- |
| **Process Isolation** | Heavy LLM tasks → `IDLE_PRIORITY_CLASS` subprocesses; Voice interface → `HIGH_PRIORITY_CLASS` — inference **never** blocks audio |
| **Dual Inference Lanes** | Separate Ollama on ports `11434` (LiveTalk) and `11435` (Sovereign Mode) — bypasses query-queue bottlenecks entirely |
| **Flatline Watchdog** | 3-second heartbeat pulses + 45-second deadlock detection → `SIGKILL` + auto-respawn with cooldown gate |
| **Three-Tier Memory** | Volatile working memory → SQLite WAL episodic store → Chroma semantic embeddings — auto-injected per inference call |
| **Agent Ecosystem** | 150+ AI personas across 13 industry domains; intent-based routing via `agent_router.py` |
| **Skill Architecture** | 58+ modular plugins (vision, WhatsApp/Gmail automation, ADB Android control) with dynamic hot-reload |
| **Evaluation Harness** | Production-grade hallucination, bias, jailbreak & OSS-vs-frontier benchmark suite → auto-generates PDF/MD reports |
| **VRAM Management** | Active GPU eviction (`keep_alive: 0`) + `gc.collect()` post-task — prevents RAM/VRAM exhaustion on long sessions |
| **IPC Layer** | Shared-nothing JSON `multiprocessing.Queue()` — no memory collision between parent/child processes on Windows `spawn` |
| **Safety Filters** | Runtime prompt injection detection + response filtering for jailbreak, violent content, and toxic language |

</details>

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

<img align="right" width="38%" src="https://github-readme-stats.vercel.app/api/pin/?username=mohamad-shafeez&repo=SafeNav&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&icon_color=7dd3fc&text_color=8b949e"/>

> *A full-stack health-aware route intelligence PWA. Synthesizes live weather, AQI, and traffic telemetry with Gemini AI to generate deterministic safety scores and health-personalized travel recommendations.*

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_1.5_Flash-8E44AD?style=flat-square&logo=google&logoColor=white)
![TomTom](https://img.shields.io/badge/TomTom_API-DF0A24?style=flat-square)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![AES256](https://img.shields.io/badge/AES--256_Fernet-00897B?style=flat-square)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)

<br clear="right"/>

<details>
<summary><b>🔬 &nbsp; Engineering Architecture — Click to Expand</b></summary>

<br/>

| 🏗️ Pillar | ⚙️ Implementation |
| :--- | :--- |
| **Deterministic Risk Engine** | Composite Safety Score (0–150) with adaptive health thresholds (31°C cardiac vs. 38°C standard) + non-linear exposure multiplier |
| **Dual-Route Intelligence** | TomTom BBox incident scanning + Haversine geodesic math + fuel/CO₂/toll modeling — fastest vs. health-optimized path comparison |
| **AI Resilience** | Gemini exponential backoff + API key rotation on 429/503; graceful degradation for all external APIs |
| **Secure Document Vault** | 22 document types — Fernet AES-256-CBC + PBKDF2-HMAC-SHA256 + SHA-256 checksums + Gemini Vision AI validation |
| **Admin Command Center** | JWT-verified kill-switch (L0–L3 threat levels) + immutable Firestore audit logs + real-time API quota monitoring |
| **Production Stack** | Render (Gunicorn) + Firebase Hosting + Vercel serverless fallback — Stale-While-Revalidate PWA offline support |

</details>

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

<img align="right" width="38%" src="https://github-readme-stats.vercel.app/api/pin/?username=mohamad-shafeez&repo=Auctin-House&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&icon_color=7dd3fc&text_color=8b949e"/>

> *High-fidelity live auction and token-draw platform. State-locked campaigns, WebSocket bid broadcasting, real-time grid locking, and a private user-admin chat system.*

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React_v19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase_Auth-FFCA28?style=flat-square&logo=firebase&logoColor=black)

<br clear="right"/>

- **Hybrid 3-Tier Listing System** — DRAW (100-slot token grid), LIVE_BID (real-time auction rooms), SOCIAL (post feed) under a unified Mongoose model
- **Real-Time WebSocket Layer** — Socket.io broadcasts bid updates, emoji reactions, and token grid locking to all clients instantly
- **State-Locked Grid** — Purchase locks token numbers in real-time preventing double-booking; MongoDB TTL auto-expires campaigns 2 days post-`endTime`
- **Admin God Mode** — User management, ban/unban toggles, campaign creator with Cloudinary media ingestion, real-time chat inbox with unread badges

<a href="https://github.com/mohamad-shafeez/Auctin-House">
  <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>

<br/><br/>

---

### 🌐 &nbsp; EventEase &mdash; AI-Augmented Event Management Platform

> *Production-ready multi-role event platform. Flask + MySQL + Gemini AI managing the full event lifecycle — creation, booking, QR ticketing, and automated background tasks.*

![Flask](https://img.shields.io/badge/Flask_3.1-000000?style=flat-square&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-8E44AD?style=flat-square&logo=google&logoColor=white)
![APScheduler](https://img.shields.io/badge/APScheduler-FF6F00?style=flat-square)
![QR](https://img.shields.io/badge/QR%20Ticketing-000000?style=flat-square)

- **Gemini AI Toolkit** — Auto-generates event descriptions, INR pricing with local market reasoning, and WhatsApp social copy
- **Full Booking Pipeline** — Ticket booking → checkout → PDF/QR ticket generation → on-site check-in scanning
- **Background Automation** — APScheduler cancels expired drafts, promotes waitlists, and syncs event statuses automatically
- **Role Dashboards** — Creator analytics (revenue, fill rates), attendee bookmarks/reviews, admin moderation with AI content flagging

<a href="https://github.com/mohamad-shafeez/EventEase">
  <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>

<br/><br/>

---

### 🗳️ &nbsp; VoteHub &mdash; Real-Time MERN Polling Platform

> *Secure voting application with JWT auth, role-based admin controls, Chart.js result visualizations, and real-time platform-wide settings toggling — no redeploy needed.*

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![ChartJS](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

- First-registered user auto-assigned Admin; JWT + bcrypt auth with Axios interceptors
- Admin toggles: enable/disable registration, open/close voting, update site name — all live, zero redeploy
- Poll deletion cascades to all associated votes; Chart.js visualizations for live results

<a href="https://github.com/mohamad-shafeez/VoteHub">
  <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<br/>

## 🛠️ &nbsp; `cat ./tech_stack.json`

<br/>

```json
{
  "languages"  :  ["Python", "JavaScript (ES6+)", "HTML5", "CSS3", "SQL"],

  "backend"    :  {
    "frameworks":   ["Node.js", "Express.js", "Flask"],
    "patterns"  :   ["REST APIs", "Event-Driven Architecture", "Multiprocessing",
                     "IPC (JSON Lines)", "CPU Priority Scheduling", "WAL Mode SQLite"],
    "security"  :   ["JWT", "RBAC", "AES-256 / Fernet", "PBKDF2-HMAC-SHA256",
                     "Firebase Auth", "bcrypt"]
  },

  "ai_ml"      :  {
    "inference" :   ["Ollama", "Gemini 1.5 Flash", "Faster-Whisper STT", "Silero VAD"],
    "memory"    :   ["Chroma Vector DB", "SQLite WAL", "Semantic Embeddings"],
    "patterns"  :   ["RAG", "Prompt Engineering", "Multi-Agent Orchestration",
                     "Tool-Use Agents", "Hallucination Detection", "Safety Filtering"]
  },

  "frontend"   :  ["React.js", "Next.js 14", "Tailwind CSS", "Framer Motion",
                   "Vanilla JavaScript", "PWA", "Service Workers", "MapLibre GL JS"],

  "databases"  :  ["MongoDB", "Firebase Firestore", "SQLite", "MySQL"],

  "realtime"   :  ["Socket.io", "WebSockets", "Server-Sent Events (SSE)"],

  "devops"     :  ["Git", "Gunicorn", "Render", "Vercel", "Firebase Hosting",
                   "Netlify", "Postman", "Cloudinary", "TomTom API", "ADB"]
}
```

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<br/>

## 📊 &nbsp; `./stats --github`

<br/>

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=mohamad-shafeez&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&icon_color=7dd3fc&text_color=c9d1d9&ring_color=00b4d8&count_private=true&include_all_commits=true"/>
&nbsp;&nbsp;
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohamad-shafeez&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&text_color=c9d1d9&langs_count=8"/>

<br/><br/>

<img width="70%" src="https://github-readme-streak-stats.herokuapp.com/?user=mohamad-shafeez&theme=github-dark-blue&hide_border=true&background=0d1117&ring=00b4d8&fire=7dd3fc&currStreakLabel=00b4d8&sideLabels=c9d1d9&dates=8b949e"/>

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<br/>

## 📬 &nbsp; `cat ./contact.txt`

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

> ### *"I don't just build features — I engineer systems."*
> *Actively seeking backend, full-stack, or AI/ML internship roles for 2026.*
> *If you're building something ambitious — I'd love to contribute.*

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,50:0a2a4a,100:020810&height=120&section=footer"/>

</div>
