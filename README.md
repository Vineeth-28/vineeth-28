<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&pause=1200&color=38BDF8&center=true&vCenter=true&width=900&lines=Backend+Engineer+%28Node.js+%7C+TypeScript%29;APIs+%7C+Redis+%7C+MongoDB+%7C+Queues+%7C+Real-time;...who+also+ships+it%3A+Docker+%7C+CI%2FCD+%7C+Terraform+%7C+AWS;I+build+it.+I+ship+it.+I+run+it." alt="Backend Engineer who knows DevOps" />

### Hi, I'm Vineet 👋 I'm a backend engineer who also knows how to ship what he builds.

**📍 Noida, India  ·  🟢 Open to Backend Engineer roles (Node.js / TypeScript)  ·  Available to join immediately**

[![Email](https://img.shields.io/badge/Email_me-VineetPrakash918%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:VineetPrakash918@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-vineeth--28.github.io-38BDF8?style=for-the-badge&logo=githubpages&logoColor=white)](https://vineeth-28.github.io)
[![AWS](https://img.shields.io/badge/AWS_SAA--C03-In_Progress-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://vineeth-28.github.io)

</div>

---

## 🎯 Why hire me

My core is backend: APIs, data models, caching, queues and real-time systems. On top of that I bring the DevOps skills most backend developers hand off, so the services I write are easy to containerize, deploy, observe and scale, and I can take them to production myself.

| Backend (my core) | Proof |
|---|---|
| **Design and build APIs** with validation, layered architecture, caching, logging and request tracing | [URL Shortener API](https://github.com/Vineeth-28/ShortUrl-) |
| **Build real-time and async systems**: Socket.IO messaging, JWT auth, background jobs with retries and rate limits | [Slack Backend](https://github.com/Vineeth-28/Slack-Backend) |

| DevOps (what makes me easier to hire) | Proof |
|---|---|
| **Take a service from `git push` to a running Kubernetes deployment** with rolling updates, monitoring and logs | [CloudBoard](https://github.com/Vineeth-28/cloudboard) |
| **Provision cloud infrastructure entirely as code**, with nothing clicked together in a console | [AWS with Terraform](https://github.com/Vineeth-28/Assignment) · [Multi-Tier Terraform](https://github.com/Vineeth-28/Multi-Tier-Terraform) |
| **Automate build → test → scan → deploy** | [DevSecOps Toolkit](https://github.com/Vineeth-28/devsecops-cheatsheets) · [Matrix CI/CD](https://github.com/Vineeth-28/Matrix-Strategy-Github-Actions) |

---

## ⭐ Start here (best 3 projects)

### 1. [URL Shortener API](https://github.com/Vineeth-28/ShortUrl-): backend
A backend-only service with validated **tRPC** procedures and compact **Base62** codes generated from an **atomic Redis counter**, so there are no collisions under concurrency. It caches URL mappings in Redis, uses a controller / service / repository structure, and adds request correlation IDs and structured **Winston** logging.
`TypeScript · Express · tRPC · MongoDB · Redis · Zod · Winston`

### 2. [Slack Backend](https://github.com/Vineeth-28/Slack-Backend): backend
A REST API and real-time messaging backend for a Slack-style platform: JWT sign-up and sign-in, workspaces with join codes and admin/member roles, channels, and messages saved to MongoDB before being broadcast over **Socket.IO**, with paginated history. It also includes **async bulk email** on BullMQ and Redis, with one job per recipient, retries with exponential backoff and a shared rate limit across workers.
`Node.js · Express · MongoDB · Socket.IO · Redis · BullMQ · JWT · Zod`

### 3. [CloudBoard](https://github.com/Vineeth-28/cloudboard): backend meets DevOps
A production-style delivery pipeline for a user-directory service. A `git push` triggers CI/CD and ends in a **monitored, logged, rolling-updated Kubernetes deployment**.
`Kubernetes · Docker · CI/CD · Monitoring`

---

## 🏗️ More projects

| Project | What it shows | Stack |
|---|---|---|
| [AWS Infrastructure with Terraform](https://github.com/Vineeth-28/Assignment) | A full AWS stack (VPC, ALB, ASG, RDS, Secrets Manager, S3) defined as code and deployed through a GitHub Actions pipeline | Terraform · AWS · GitHub Actions |
| [URL Shortener: Containerized & Deployed](https://github.com/Vineeth-28/url-shortener-service) | A service I built **and then productionized**: Dockerized, health-checked, deployed via CI/CD | Docker · GitHub Actions · Node.js · Redis |
| [Multi-Tier-Terraform](https://github.com/Vineeth-28/Multi-Tier-Terraform) | Modular, variable-driven multi-tier AWS architecture (VPC, subnets, EC2, security groups) | Terraform · AWS |
| [DevSecOps CI/CD Toolkit](https://github.com/Vineeth-28/devsecops-cheatsheets) | Reusable workflows with **Trivy** (CVE) and **Gitleaks** (secrets) scanning | GitHub Actions · Docker |
| [Matrix Testing & Deployment](https://github.com/Vineeth-28/Matrix-Strategy-Github-Actions) | 3-stage pipeline: matrix tests across Python versions → Docker build & push → deploy via self-hosted runner | GitHub Actions · Docker · Python |
| [Ubuntu Provisioning Script](https://github.com/Vineeth-28/Starting-Shell-Script-for-Ubuntu-) | One script to provision, secure and configure an AWS Ubuntu instance with Docker | Bash · AWS · Docker |

---

## 🛠️ Tech stack

| | |
|---|---|
| 💻 **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![tRPC](https://img.shields.io/badge/tRPC-398CCB?style=flat-square&logo=trpc&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) ![BullMQ](https://img.shields.io/badge/BullMQ-DC382D?style=flat-square) |
| 🗄️ **Data** | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white) |
| 📦 **Containers & IaC** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) |
| ☁️ **Cloud** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=FF9900) ![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white) ![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white) ![IAM](https://img.shields.io/badge/IAM-DD344C?style=flat-square&logo=amazoniam&logoColor=white) |
| ⚙️ **CI/CD & Security** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aquasecurity&logoColor=white) |
| 🐧 **Linux & Scripting** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) |
| 🔀 **Version Control** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |

**Learning now:** Go · system design (HLD) · DSA · Helm · Kubernetes in production (HPA, Ingress)

---

## 🧭 How I work

- **Backend first:** clean layering (controllers, services, repositories), validated inputs and clear errors
- **Observable from day one:** structured logs, health checks and request tracing, not bolted on later
- **Everything as code:** infrastructure, pipelines and config live in Git and are reproducible
- **Secure pipelines:** my DevSecOps toolkit scans images (Trivy) and secrets (Gitleaks) before anything ships
- **Documented:** each repo explains setup steps and the reasoning behind design decisions

---

## 📊 GitHub activity

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=Vineeth-28&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Vineeth-28&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🎓 Currently working on

- 🧩 Deeper backend work: system design, data structures and algorithms, Go, and tests for my APIs
- ☸️ Kubernetes production deployment: manifests, probes, HPA, Ingress, monitoring and logging
- 🎓 AWS Certified Solutions Architect – Associate (SAA-C03), in progress

---

## 📫 Let's talk

I'm looking for a **Backend Engineer** role (Node.js / TypeScript) where I can own services from code to production. My DevOps background also fits Platform and Cloud teams.

📧 **[VineetPrakash918@gmail.com](mailto:VineetPrakash918@gmail.com)**  ·  🌐 **[vineeth-28.github.io](https://vineeth-28.github.io)**  ·  📍 Noida, India

<div align="center">

### ⚡ Build Reliable Services • Ship Them Yourself • Keep Learning

</div>
