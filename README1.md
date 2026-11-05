<h1 align="center">Hey, I'm Atharva 👋</h1>

<p align="center">
  <b>while(alive) { build(); break; }</b><br/>
  CS undergrad at IIIT Jabalpur building backend systems, security tooling and ML pipelines.
</p>

<p align="center">
  <img src="https://img.shields.io/github/followers/atharva486?style=for-the-badge&logo=github&label=Followers&color=1f6feb" alt="Followers"/>
  <img src="https://img.shields.io/badge/CGPA-8.8%2F10-2ea043?style=for-the-badge" alt="CGPA 8.8"/>
  <img src="https://komarev.com/ghpvc/?username=atharva486&style=for-the-badge&label=Profile+views&color=8957e5" alt="Profile views"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/atharva-ghogare"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:atharva486adg@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## About me

- 🎓 **Studying:** B.Tech in Computer Science and Engineering at **IIIT Jabalpur** (2024 to 2028), CGPA 8.8/10
- 🔭 **Building now:** Sentinel-AI, a Layer-7 DDoS detection pipeline
- 🧠 **Interested in:** backend engineering, networking and security, applied ML
- 📍 **Based in:** Pune, India
- 🏆 **Competitive programmer:** 1,200+ problems solved
- ⚡ **Fun fact:** my bio is an infinite loop that breaks on the first run.

---

## Featured projects

### 🛡️ Sentinel-AI: Layer-7 DDoS detection pipeline
*Python · XGBoost · Docker · SHAP*

- Built a self-hosted Docker testbed that generates realistic Layer-7 DDoS traffic and labels every flow at the source: **5,337 labelled flows** across 11 capture runs.
- Trained an XGBoost detector on 16 decision-time features (**0.84 PR-AUC, 0.81 ROC-AUC**). Isotonic calibration cut expected calibration error about 13x (0.066 to 0.005).
- Found and fixed two silent data-corruption bugs, then enforced a leakage-safe train/test split.
- Per-connection SHAP explanations drive a four-way response (forward, throttle, block, quarantine), holding **false positives at zero** (100% precision, 75% recall) on held-out traffic.

### 📈 PortfolioX: high-performance trading portfolio backend
*Python · FastAPI · PostgreSQL · SQLAlchemy · asyncio · Docker · GitHub Actions*

- Layered trading backend (2,562 LOC, 11 REST endpoints). Parallel price fetching with `asyncio.gather()` cut **p95 latency 35%** (3.19s to 2.06s).
- Fixed a race condition where simultaneous trades could overspend a balance, using PostgreSQL row-level locking and advisory locks. **0 overspend cases** on real PostgreSQL.
- CI/CD on every push: Ruff, `mypy --strict`, tests, coverage, Docker image to GHCR, deployed to Cloud Run.

### 🚁 Autonomous drone tracking system *(patent pending)*
*Python · YOLOv8 · PyTorch · OpenCV · Webots · Kalman filter*

- One of 5 core developers. Fused a custom-trained YOLOv8 detector with an 8-state Kalman filter to hit **85% interception success** across 30 simulations at 20Hz. Co-authored the paper (code under NDA).

---

## Tech stack

**Languages**

<img src="https://skillicons.dev/icons?i=c,cpp,py,java,js,ts" alt="C, C++, Python, Java, JavaScript, TypeScript"/>

**Backend and databases**

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,postgres,mysql,mongodb" alt="FastAPI, Node.js, Express, PostgreSQL, MySQL, MongoDB"/>

**AI / ML**

<img src="https://skillicons.dev/icons?i=pytorch,opencv" alt="PyTorch, OpenCV"/>

XGBoost · SHAP · YOLOv8 · Google Gemini API

**DevOps and tools**

<img src="https://skillicons.dev/icons?i=docker,git,github,githubactions,linux" alt="Docker, Git, GitHub, GitHub Actions, Linux"/>

**Also comfortable with:** TCP/IP, DNS, HTTP/HTTPS, TLS/SSL, JWT authentication, REST API design, SQLAlchemy, asyncio, concurrency, mypy, Ruff, unit testing

**Core CS:** Data Structures and Algorithms, Operating Systems, DBMS, Computer Networks, OOP, Cryptography and Network Security, Probability and Statistics

---

## Achievements

- 🏅 **Infinity Hacks 2026:** ranked **21st of 300 teams** for GlobalTrack, a distributed multi-agent target-tracking system
- 🥇 **CodeRumble 4.0:** 5th place (Sep 2026)
- 🥈 **Newbie 2.0 Coding Contest:** 2nd place (Apr 2025)
- 🏆 **Intra-College Summer Hackathon:** top 5
- 📄 **Research and patent:** co-authored a paper on predictive forecasting under uncertainty, and filed a provisional patent for the drone tracking pipeline

**Competitive programming**

| Platform | Rating |
| --- | --- |
| LeetCode | 1802 |
| Codeforces | 1417 |
| CodeChef | 1700 (global rank 231) |

**Certifications:** Networking Basics (Cisco Networking Academy) · REST API (HackerRank)

---

## GitHub stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=atharva486&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=atharva486&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=atharva486&theme=tokyonight&hide_border=true" alt="Contribution streak"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=atharva486&theme=tokyonight&no-frame=true&row=1&column=6" alt="GitHub trophies"/>
</p>

**GitHub achievements:** Quickdraw (closed an issue or PR within 5 minutes) and Pull Shark (merged pull requests).

---

## Let's connect

Open to internships, hackathon teams and interesting backend or security problems. Reach me on [LinkedIn](https://www.linkedin.com/in/atharva-ghogare) or by [email](mailto:atharva486adg@gmail.com).
