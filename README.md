<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Atharva%20Datta%20Ghogare&fontSize=48&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Backend%20%C2%B7%20Security%20%C2%B7%20Machine%20Learning&descSize=20&descAlignY=60" alt="Atharva Datta Ghogare"/>
</p>

<!-- Typing headline -->
<p align="center">
  <a href="https://github.com/atharva486">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1400&color=58A6FF&center=true&vCenter=true&width=720&lines=while(alive)+%7B+build()%3B+break%3B+%7D;Ranked+21st+of+300+teams+at+Infinity+Hacks+2026;Patent-pending+autonomous+drone+tracking;Detecting+DDoS+attacks+with+explainable+ML;1%2C200%2B+problems+solved+%7C+LeetCode+Knight+(1883)" alt="Typing intro"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/IIIT%20Jabalpur-CSE%20'28-0A66C2?style=for-the-badge" alt="IIIT Jabalpur"/>
  <img src="https://img.shields.io/badge/CGPA-8.8%2F10-2ea043?style=for-the-badge" alt="CGPA 8.8"/>
  <img src="https://img.shields.io/badge/Based%20in-Pune%2C%20India-e5534b?style=for-the-badge" alt="Pune, India"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/atharva-ghogare"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:atharva486adg@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 👨‍💻 Who I am

I'm a Computer Science student at **IIIT Jabalpur** who likes problems where the system has to be fast, correct and hard to break. I build backends that hold up under load, security tooling that explains its decisions, and ML pipelines that get checked for leakage before anyone trusts the numbers.

Outside of class I compete: hackathons, contests and research. I've co-authored a paper and filed a provisional patent before finishing my second year.

---

## 📊 By the numbers

| | |
| :--- | :--- |
| 🏅 **21st of 300** | teams at Infinity Hacks 2026 |
| 🧮 **1,200+** | problems solved across LeetCode, Codeforces and CodeChef |
| 🥇 **LeetCode Knight** | rated 1883, with a 1732 CodeChef and 1432 Codeforces rating |
| 🛡️ **0 false positives** | in Sentinel-AI's response ablation on held-out traffic |
| ⚡ **35% faster** | p95 latency in PortfolioX after parallelising price fetching |
| 🎯 **85% interception** | across 30 drone-tracking simulations at 20Hz |
| 📉 **13x better calibration** | on the DDoS detector after isotonic calibration |

---

## 🚀 Featured projects

### 🛡️ Sentinel-AI: Layer-7 DDoS detection pipeline
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/XGBoost-EC6B23?style=flat-square"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/SHAP-8957e5?style=flat-square"/>

An end-to-end system that detects application-layer DDoS traffic and explains why it flagged each connection.

- Built a self-hosted Docker testbed that generates realistic Layer-7 attack traffic and labels every flow at the source: **5,337 labelled flows** across 11 capture runs.
- Trained an XGBoost detector on 16 decision-time features: **0.84 PR-AUC, 0.81 ROC-AUC**. Isotonic calibration cut expected calibration error from 0.066 to 0.005.
- Caught and fixed two silent data-corruption bugs, then enforced a leakage-safe train/test split so the results are honest.
- Per-connection SHAP explanations drive a four-way response (forward, throttle, block, quarantine), with **100% precision and 75% recall** on held-out traffic.

### 📈 PortfolioX: high-performance trading portfolio backend
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>

A layered trading backend (2,562 LOC, 11 REST endpoints) with a live API.

- Parallel price fetching with `asyncio.gather()` cut **p95 latency by 35%** (3.19s to 2.06s).
- Solved a concurrency race where simultaneous trades could overspend a balance, using PostgreSQL row-level and advisory locks. **Zero overspend cases** on real PostgreSQL, not a SQLite stand-in.
- Ship-on-every-push pipeline: Ruff, `mypy --strict`, tests, coverage, Docker image to GHCR, then deploy to Cloud Run.

### 🚁 Autonomous drone tracking system *(patent pending)*
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/> <img src="https://img.shields.io/badge/YOLOv8-111F68?style=flat-square"/>

One of 5 core developers. We fused a custom-trained YOLOv8 detector with an 8-state Kalman filter and reached **85% interception success** across 30 simulations at 20Hz. Co-authored the resulting paper; the code is under NDA.

---

## 🛠️ Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=c,cpp,py,java,js,ts&perline=6" alt="Languages"/>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,postgres,mysql,mongodb&perline=6" alt="Backend and databases"/>
</p>
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,opencv,docker,git,github,githubactions,linux&perline=7" alt="ML and tools"/>
</p>

**Networking and security:** TCP/IP · DNS · HTTP/HTTPS · TLS/SSL · HTTP proxies · API security · DDoS detection
**Backend:** REST APIs · JWT authentication · asyncio · concurrency · SQLAlchemy · performance optimisation
**AI/ML:** XGBoost · SHAP · YOLOv8 · Kalman filtering · Google Gemini API
**Engineering:** CI/CD · Docker Compose · mypy · Ruff · unit testing · debugging
**Core CS:** DSA · Operating Systems · DBMS · Computer Networks · OOP · Cryptography · Probability and Statistics

---

## 🏆 Achievements

- 🏅 **Infinity Hacks 2026:** 21st of 300 teams for GlobalTrack, a distributed multi-agent target-tracking system
- 🥇 **CodeRumble 4.0:** 5th place
- 🥈 **Newbie 2.0 Coding Contest:** 2nd place
- 🏆 **Intra-College Summer Hackathon:** top 5
- 📄 **Research:** co-authored a paper on predictive forecasting under uncertainty
- 💡 **Patent:** provisional patent filed for the autonomous drone tracking pipeline
- 🎖️ **Certified:** Networking Basics (Cisco Networking Academy), REST API (HackerRank)

**Competitive programming**

<p>
  <img src="https://img.shields.io/badge/LeetCode-1883-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode 1883"/>
  <img src="https://img.shields.io/badge/LeetCode-Knight-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode Knight badge"/>
  <img src="https://img.shields.io/badge/Codeforces-1432-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces 1432"/>
  <img src="https://img.shields.io/badge/CodeChef-1732-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef 1732"/>
</p>

---

## 📈 What I code in

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=atharva486&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages"/>
</p>

**GitHub achievements:** ⚡ Quickdraw · 🦈 Pull Shark

---

## 🤝 Let's work together

I'm looking for internships and teams working on backend systems, security or applied ML. If you've got a hard problem, reach me on [LinkedIn](https://www.linkedin.com/in/atharva-ghogare) or by [email](mailto:atharva486adg@gmail.com).

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" alt=""/>
</p>
