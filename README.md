<h1 align="center">Hi, I'm Shankar 👋</h1>
<h3 align="center">Backend / Infrastructure Engineer — I build the systems that keep other systems honest</h3>

<p align="center">
  Final-year CSE @ NIT Andhra Pradesh &nbsp;•&nbsp; Hyderabad, India &nbsp;•&nbsp; Open to SDE & Infra roles
</p>

<p align="center">
  <a href="https://linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"></a>
  <a href="mailto:munig.shankar@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"></a>
  <a href="https://dexterrenders.my.canva.site"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white"></a>
</p>

---

### 🔭 What I'm building

I care about the boring, invisible layer of software — the proxies, rate limiters, and control loops that decide whether a system falls over under load or bends gracefully.

**[Floodgate](https://github.com/DexterDebugs/Floodgate)** — an adaptive API gateway in Go.
It's not just a reverse proxy with rate limiting bolted on. It watches its own rolling p95 latency and error rate, and feeds that signal into a **PID controller** that adaptively tightens or loosens rate limits in real time — the same control-theory idea that keeps a thermostat from overshooting, applied to traffic shaping. Redis-backed atomic limiters, Prometheus/Grafana observability, shipped as a 22MB distroless Docker image.

> Currently mid-fix on an **integral wind-up bug** — under sustained slow traffic the controller's output climbs to 265 when 9 would do the job. That's the kind of failure mode you only find by actually running the system, not by reading about PID controllers.

### 🧰 Other things I've shipped

- **[redis-go](https://github.com/DexterDebugs/redis-go)** — Redis-compatible in-memory store built from scratch in Go: raw TCP, hand-rolled RESP protocol parsing, mutex-guarded state, lazy key expiration.
- **[BloodConnect](https://github.com/DexterDebugs/Blood-Donation-System)** — FastAPI + PostgreSQL + Gemini AI blood donation platform, containerized end-to-end.
- **[Sphere](#)** — React matching platform using Jaccard similarity + the Claude API.

### 🛠️ Tech I work with

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white">
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white">
</p>

### 📊 GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DexterDebugs&show_icons=true&theme=tokyonight&hide_border=true" height="165">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=DexterDebugs&theme=tokyonight&hide_border=true" height="165">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DexterDebugs&layout=compact&theme=tokyonight&hide_border=true&langs_count=6">
</p>

---

<p align="center"><i>Also into 3D product animation & graphic design — see the portfolio link above.</i></p>
