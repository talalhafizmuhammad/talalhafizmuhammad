<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00FFFF&center=true&width=600&lines=Hi%2C+I'm+Hafiz+Muhammad+Talal;AI+%2F+DevOps+Engineer;Backend+%7C+MLOps+%7C+Infrastructure;CS+Student+%40+PUCIT" />
</h1>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=talalhafizmuhammad&style=flat-square&color=00ffee" alt="profile views" />
</p>

---

## About Me

I'm an **AI/DevOps Engineer** building production-ready systems — from infrastructure automation to AI-powered applications. Backend development is a core supporting skill, not the main focus. I believe in shipping things that actually run in production, not just tutorials that work on localhost.

Currently a Computer Science student at **PUCIT** (Punjab University College of Information Technology), and actively building **Gesty**, a premium hospitality invitation platform for the Saudi Arabian market.

---

## Areas of Expertise

> Following are the areas of tech I have hands-on experience in and have shipped real projects with:

### 1. DevOps & Infrastructure
- Containerization & Orchestration (Docker, Kubernetes — in progress)
- Infrastructure as Code (Terraform — in progress, Ansible)
- CI/CD Pipelines (GitHub Actions)
- Web Servers & Reverse Proxy (Nginx)
- Cloud (AWS — EC2, RDS, S3)
- Linux Systems Administration (Bash scripting, process management)

### 2. AI / ML / Agentic Systems
- LLM Integration (OpenRouter, Anthropic Claude API, Gemini)
- Agentic AI Workflows (LangChain, LangGraph)
- Workflow Automation (n8n)
- Data Analysis & Visualization (Pandas, NumPy, Matplotlib, Seaborn)
- Classical ML (Scikit-Learn, TensorFlow)

### 3. Backend Engineering
- API Development (FastAPI, Express.js, NestJS)
- Databases (PostgreSQL, Supabase, Prisma ORM)
- Async Job Processing (BullMQ, Redis)
- Authentication (JWT, RBAC, bcrypt)
- Realtime Systems (Supabase Realtime, WebSockets)

### 4. Frontend (Supporting Skill)
- React.js, Next.js
- Tailwind CSS

---

## Portfolio Projects

### AlertMind — AI-Powered On-Call Assistant
**Live:** [alertmind-dashboard.vercel.app](https://alertmind-dashboard.vercel.app/)

- Receives infrastructure alerts (CPU, memory, latency, error rate) via FastAPI webhooks
- Correlates alerts with real GitHub commit history to identify the exact guilty commit and author
- AI root cause analysis using Gemini via OpenRouter with structured output parsing
- Posts diagnosis + fix suggestion to Slack with interactive Block Kit buttons (Acknowledge / Resolve)
- Real-time Next.js dashboard with search, filters, and alert history
- Stripe billing integration with tiered subscription plans
- Full Docker + GitHub Actions CI/CD pipeline

**Tech Stack:** `Python` · `FastAPI` · `Next.js` · `PostgreSQL` · `Supabase` · `Docker` · `GitHub Actions` · `OpenRouter` · `Slack SDK` · `Stripe`

---

### University Management Portal — Production App, 65+ Active Students
**Live:** [university-portal-frontend-nu.vercel.app](https://university-portal-frontend-nu.vercel.app/)

- Full grade management system with PU's weighted grading logic (Sessionals/Midterm/Final)
- JWT authentication with bcrypt hashing, rate limiting, and role-based access (Admin/TA/Student)
- CSV bulk marks import — TAs upload an entire class roster in one shot
- Marks analytics: class average, pass rate, per-assessment breakdowns
- Student ranking & comparison against class average (fully anonymized)
- Mark change audit log — every edit tracked with who changed what and when
- PDF transcript export and full JSON data backup
- **v2 rebuild:** migrated from Railway to Vercel Serverless + Supabase with PgBouncer connection pooling after production database failures during exam season — fixed serverless/Postgres connection mismatches under real load

**Tech Stack:** `React.js` · `Node.js` · `Express.js` · `PostgreSQL` · `Supabase` · `Prisma ORM` · `JWT` · `Vercel`

---

### CipherGuard — DSA-Based Cybersecurity Analyzer
**Live:** [cipher-guard-gamma.vercel.app](https://cipher-guard-gamma.vercel.app/)

A full-stack cybersecurity toolkit covering multiple attack surfaces and defensive utilities, with core logic built on data structures and algorithms:

- `anomaly_detector` — behavioral anomaly detection in system logs
- `cipher_breaker` — classical cipher analysis & breaking
- `file_integrity` — file hash verification & tamper detection
- `password_analyzer` / `password_vault` — strength scoring & encrypted credential storage
- `rsa_generator` — RSA key pair generation
- `steganography` — image-based data hiding & extraction
- `threat_graph` — threat relationship mapping using graph structures
- `log_generator` — synthetic log generation for testing

**Tech Stack:** `Python` · `FastAPI` · `React.js` · `Cryptography` · `DSA (Graphs, Hash Maps, Trees)` · `Vercel`

---

### Gesty — Premium Hospitality Invitation Platform *(In Development)*

A three-actor digital invite and venue redemption platform (Sender, Recipient, Merchant) built for the Saudi Arabian luxury events market.

- Full KSA regulatory compliance: SAMA, ZATCA FATOORA e-invoicing, PDPL
- Arabic RTL as a Day 1 requirement
- Mada and STC Pay payment integration
- Web-based flows to avoid platform in-app purchase cuts
- AI features structured as async background jobs

**Tech Stack:** `Node.js` · `PostgreSQL` · `Supabase` · `BullMQ` · `AWS (RDS Bahrain)` · `Claude API` · `RBAC`

---

## Tech Stack

#### Languages
`Python` · `C/C++` · `JavaScript` · `TypeScript` · `SQL` · `Bash`

#### DevOps & Infrastructure
<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
</p>

#### AI / ML / Automation
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-1F77B4?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenRouter-6C47FF?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white"/>
</p>

#### Backend & Databases
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST_APIs-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/BullMQ-FF0000?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

#### Frontend
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
</p>

#### Systems & Languages
<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white"/>
</p>

#### Developer Tools
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
</p>

---

## Engineering Focus

I focus on building **clean, automated, production-grade systems** with an emphasis on:

- Automation-first workflows — if it can be scripted or scheduled, it shouldn't be manual
- Infrastructure that doesn't break under real-world load (learned this the hard way during exam season)
- AI features designed as async background jobs, not blocking request paths
- Compliance and security built in from day one, not retrofitted later

---

## GitHub Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=talalhafizmuhammad&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=talalhafizmuhammad&theme=tokyonight" height="160"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=talalhafizmuhammad&theme=tokyonight" height="160"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=talalhafizmuhammad&theme=tokyonight&hide_border=true" height="160" />
</p>

### 3D Contribution Graph

<p align="center">
  <img src="./profile-3d-contrib/profile-night-green.svg" alt="3D contribution graph" />
</p>

### Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/talalhafizmuhammad/talalhafizmuhammad/output/github-snake-dark.svg" alt="contribution snake animation" />
</p>

<table align="center">
  <tr>
    <td align="center"><strong>GitHub Heatmap</strong><br><br>
      <img src="https://ghchart.rshah.org/00FFFF/talalhafizmuhammad" alt="GitHub Contribution Chart" height="180">
    </td>
    <td align="center"><strong>LeetCode Stats</strong><br><br>
      <img src="https://leetcard.jacoblin.cool/talalhafizmuhammed?theme=dark&ext=heatmap" alt="LeetCode Streak" height="180">
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=talalhafizmuhammad&theme=tokyo-night&area=true&hide_border=true" />
</p>

---

## Connect With Me

<p align="center">
  <a href="mailto:muhammadtala20201@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/hafiz-muhammad-talal"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/talalhafizmuhammad"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

<p align="center">
  <i>"The quieter you become, the more you are able to hear." – Maulana Rumi</i>
</p>
