<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00FFFF&center=true&width=600&lines=Hey%2C+I'm+Hafiz+Muhammad+Talal+%F0%9F%91%8B;AI+%2F+DevOps+Engineer;Backend+%7C+MLOps+%7C+Infrastructure;CS+Student+%40+PUCIT" />
</h1>

<p align="center">
  🤖 AI/MLOps Engineer &nbsp;|&nbsp; 🛠️ DevOps & Infrastructure &nbsp;|&nbsp; ⚙️ Backend Developer &nbsp;|&nbsp; 🐧 Linux Enthusiast
</p>

<p align="center">
  Building intelligent systems, automating infrastructure, and shipping reliable backend services.
</p>

---

### 🧰 Core Stack

#### 🚀 DevOps & Infrastructure
<p align="center">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
</p>

#### 🤖 AI / ML / MLOps
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-1F77B4?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white"/>
</p>

#### ⚙️ Backend & Systems
<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST_APIs-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/BullMQ-FF0000?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white"/>
</p>

#### 📚 Currently Learning
<p align="center">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
</p>

---

### 🚀 Projects

---

#### 🔔 [AlertMind]([https://alertmind-dashboard.vercel.app/]) — AI-Powered On-Call Assistant for Engineering Teams
> *Server alert fires at 3 AM. AlertMind wakes up instead of you.*

AlertMind receives infrastructure alerts (CPU, memory, latency, error rate), correlates them with real GitHub commit history, uses AI to pinpoint the exact guilty commit and author, then posts a full diagnosis + fix suggestion to Slack — in seconds.

**What I built:**
- FastAPI webhook engine for real-time alert ingestion
- AI root cause analysis via Gemini (OpenRouter) with structured output parsing
- GitHub API commit correlation & duplicate detection with time-window filtering
- Slack bot with interactive Block Kit buttons (Acknowledge / Resolve)
- Real-time Next.js dashboard with search, filters & alert history
- Stripe billing integration ($29 / $149 / $299/month tiers)
- Docker + GitHub Actions CI/CD pipeline, deployed on Vercel + Serverless

**Stack:** `Python` `FastAPI` `Next.js` `PostgreSQL` `Supabase` `Docker` `GitHub Actions` `Slack SDK` `GitHub API` `OpenRouter (Gemini)` `Stripe` `Ubuntu`

**Live:** [Dashboard](https://alertmind-dashboard.vercel.app/) · [GitHub](https://github.com/talalhafizmuhammad/alertmind-dashboard)

---

#### 🎓 [University Management Portal](https://university-portal-frontend-nu.vercel.app/) — Production App Used by 65+ Students @ PUCIT
> *Built it. Broke it during exam season. Rebuilt it properly.*

A full portal for managing courses, assessments, and student grades with PU's weighted grading system. v1 was a learning project. v2 is a production-grade rebuild after real usage exposed real problems.

**What I built:**
- JWT auth with bcrypt, rate limiting & role-based course access (Admin / TA / Student)
- CSV bulk marks import — TAs upload entire class in one shot
- Marks analytics: class average, pass rate, per-assessment breakdowns
- Student ranking & comparison against class average (anonymized)
- Email notifications for marks + announcements with expiring password reset tokens
- Mark change audit log — every edit tracked with who changed what and when
- PDF transcript export & full JSON data backup
- Migrated from Railway → Vercel Serverless + Supabase with PgBouncer connection pooling after production DB failures during exam cycle

**Stack:** `React.js` `Node.js` `Express.js` `PostgreSQL` `Supabase` `Prisma ORM` `JWT` `Vercel`

---

#### 🔐 [CipherGuard](https://cipher-guard-gamma.vercel.app/) — DSA-Based Cybersecurity Analyzer
> *A multi-tool cybersecurity suite built on core CS fundamentals.*

A Python + React full-stack cybersecurity toolkit covering multiple attack surfaces and defensive utilities, all backed by DSA-driven logic.

**Modules:**
- `anomaly_detector.py` — behavioral anomaly detection in system logs
- `cipher_breaker.py` — classical cipher analysis & breaking
- `file_integrity.py` — file hash verification & tamper detection
- `password_analyzer.py` — strength analysis & entropy scoring
- `password_vault.py` — encrypted local credential storage
- `rsa_generator.py` — RSA key pair generation
- `steganography.py` — image-based data hiding & extraction
- `threat_graph.py` — threat relationship mapping using graph structures
- `log_generator.py` — synthetic log generation for testing

**Stack:** `Python` `FastAPI` `React.js` `DSA (Graphs, Hash Maps, Trees)` `Cryptography` `Vercel`

---

#### 💌 Gesty *(In Development)* — Premium Hospitality Invitation Platform
> *Targeting the Saudi Arabian luxury events market.*

A three-actor platform (Sender, Recipient, Merchant) for premium digital invitations with full KSA compliance — SAMA, ZATCA VAT, PDPL, Arabic RTL, Mada/STC Pay integration.

**Stack:** `Node.js` `PostgreSQL` `Supabase` `BullMQ` `AWS (RDS Bahrain)` `Anthropic Claude API` `RBAC`

---

### 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=talalhafizmuhammad&show_icons=true&theme=tokyonight&count_private=true&include_all_commits=true" height="160" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=talalhafizmuhammad&layout=compact&langs_count=10&theme=tokyonight" />
</p>

---

### 🔥 GitHub Streak

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=talalhafizmuhammad&theme=tokyonight" height="160" />
</p>

---

### 🧠 Daily Coding Activity

<table align="center">
  <tr>
    <td align="center"><strong>🔥 GitHub Heatmap</strong><br><br>
      <img src="https://ghchart.rshah.org/00FFFF/talalhafizmuhammad" alt="GitHub Contribution Chart" height="180">
    </td>
    <td align="center"><strong>🧠 LeetCode Stats</strong><br><br>
      <img src="https://leetcard.jacoblin.cool/talalhafizmuhammed?theme=dark&ext=heatmap" alt="LeetCode Streak" height="180">
    </td>
  </tr>
</table>

---

### 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=talalhafizmuhammad&theme=tokyonight&margin-w=10&margin-h=10&no-frame=true&rank=SECRET,SSS,SS,S,AAA,AA,A,B,C" />
</p>

---

### 📊 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=talalhafizmuhammad&theme=tokyo-night&area=true&hide_border=true" />
</p>

---

### 📍 Visitor Counter

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=talalhafizmuhammad&style=flat-square&color=00ffee" alt="visitor counter" />
</p>

---

### 🤝 Connect With Me

<p align="center">
  <a href="mailto:muhammadtala20201@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/hafiz-muhammad-talal"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/talalhafizmuhammad"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

### 💬 Quote That Drives Me

> **"The quieter you become, the more you are able to hear."** – Maulana Rumi
