# Hi, I’m Sanskar Vidyarthi 👋
*M.Eng. Software Engineering @ University of Maryland College Park (May 2026)*  
**Software Engineer — Web Dev • Cloud • DevOps • Networking**

- I build back-end services, security automation, and network tooling.  
- Comfortable across **Python** and **C/C++** on **Linux/Windows**, with cloud infra in **AWS/GCP**, **Terraform**, **Docker**, **Kubernetes** and **GitHub Actions**.  
- Interested in **network test/observability**, **embedded basics**, and **production reliability**.

---

## 🔎 Highlights (2+ Years of Experience)
- Shipped **20+ REST APIs** (Python/Flask), fixed **40+ defects**, and wrote **80+ PyTest** cases → higher reliability & maintainability.  
- Built a serverless **CVE alerting** workflow (AWS Lambda/EventBridge/PostgreSQL) with idempotency → **3-hour detection SLA** and zero duplicate notifications.  
- Deployed a GitHub App–based **secret scanner** (Lambda/SQS/Fargate/Gitleaks) with PR checks → **~60% reduction** in credential exposure; **~50%** less manual review.  
- Provisioned **EKS via Terraform**, deployed **OpenTelemetry** with Helm, added CI/CD with rollback and **Prometheus/Alertmanager → Slack** → faster, auditable releases.

---

## 🛠️ Tech Stack
**Languages:** Python, HTML, CSS, JavaScript, Flask, XML, JSON, YAML, C++, CMake 
**Systems & Networking:** Linux, Windows, TCP/UDP sockets, libpcap, Wireshark, WSL 
**Cloud & IaC:** AWS, GCP, Terraform, Docker, GitHub Actions, Kubernetes (EKS), Helm, Docker 
**Full-stack & Data:** Flask,  React, Next.js, PostgreSQL/MySQL, BigQuery, Looker
**Tools & Platforms:** Git, Postman, JIRA, Confluence, Swagger, Linux OS, PyTest

> Full certifications: GCP **Professional Cloud Architect**, **Associate Cloud Engineer**, **AZ-900** Azure Fundamentals, Cisco **CCST Networking**

---

## 📦 Selected Projects
### NetScope — C++/libpcap Packet Analyzer (Windows/WSL)
- **Built** a packet analyzer decoding Ethernet/IPv4/TCP/UDP and surfacing “top talkers and flows” to pinpoint bandwidth hogs and flaky services.  
- **Productionized** with **CMake**; added **DNS-based domain labeling** and **TCP handshake metrics** (SYN→SYN/ACK RTT, fail rate) to reveal latency/reachability issues.  
**Tech:** C++, libpcap, CMake, Wireshark

### OpenTelemetry Observability on AWS EKS
- **Provisioned** **EKS with Terraform** (private node groups/IAM), deployed **OpenTelemetry** via **Helm**, and exposed services with LoadBalancer for **Jaeger/Grafana** diagnostics.  
- **Implemented** **GitHub Actions** CI/CD with rollback-on-failure and **Prometheus/Alertmanager → Slack** alerting.  
**Tech:** AWS, EKS, Terraform, Helm, OpenTelemetry, Prometheus, Grafana, Jaeger, GitHub Actions

### Security Automation — CVE Alerts & Secret Scanning
- **CVE pipeline:** AWS Lambda/EventBridge/PostgreSQL; idempotent processing; **3-hour** SLA; zero dupes.  
- **Secret scanner:** GitHub App + Lambda/SQS/Fargate + Gitleaks; enforced PR status checks; **~60%** credential risk reduction.  
**Tech:** Python, AWS (Lambda, SQS, Fargate), GitHub App, Gitleaks, Office 365

### Driver Drowsiness Detection (Real-Time)
- **Engineered** EAR/MAR-based detection (OpenCV/dlib) + Arduino pulse telemetry to cloud; **~90%** accuracy in controlled tests.  
**Tech:** Python, OpenCV, dlib, Arduino, ThingSpeak

---

## 💼 Experience (Deep Dive)

<details>
<summary><b>CBTS — Software Developer Intern</b> · Security automation, cloud, reliability</summary>

**Context:** Joined to harden developer workflows and reduce security toil.

- **CVE Alerting (serverless)**
  - **Problem:** Vendor CVEs arriving ad-hoc → duplicates and delayed triage.
  - **Approach:** Built an idempotent pipeline on **AWS (Lambda, EventBridge, PostgreSQL)** to ingest/parse advisories every 3 hours; added **structured logs/metrics** and O365 notifications with runbooks.
  - **Impact:** **3-hour detection SLA**, eliminated duplicate alerts, faster routing to owners.

- **Secret Scanning (merge protection)**
  - **Problem:** Credentials occasionally landed in PRs; manual review was noisy.
  - **Approach:** Developed a **GitHub App** workflow with **Lambda, SQS, Fargate, Gitleaks**; enforced **PR status checks** so risk never merged.
  - **Impact:** **~60% reduction** in credential-exposure incidents; **~50% less** manual review. 

- **Quality & Ops**
  - **What I added:** CI checks (lint/tests), policy gates, incident docs; verified across **Linux/Windows** environments.

**Tech:** Python, AWS (Lambda/SQS/Fargate/EventBridge), PostgreSQL, GitHub App/Checks API, Gitleaks, Office 365, GitHub Actions, logging/metrics
</details>

<details>
<summary><b>Accenture — Software Developer I</b> · APIs at scale, cloud delivery, observability</summary>

- **API Platform**
  - **Built:** **20+ Python/Flask REST APIs**, fully documented (**Swagger/Postman**).
  - **Quality:** **80+ PyTest** cases; **40+ defects** resolved → higher reliability & maintainability.

- **Cloud Release Engineering**
  - **Automated:** Deployments with **Docker + Terraform (GCP)**; addressed **100+ Artifact Registry** issues.
  - **Outcome:** **~40% faster** release cycles; stabilized build/publish paths.

- **Observability & Data**
  - **Delivered:** **20+ Looker (LookML)** dashboards; Python data flows with **BigQuery + Cloud Scheduler** and **10+ Cloud Monitoring** policies for SIEM/SOAR visibility.

- **Dev Practices**
  - **Standardized:** API patterns, test templates, and POC docs (**50+**) to accelerate onboarding and code reuse.

**Tech:** Python/Flask, SQL, Postman/Swagger, Docker, Terraform (GCP), BigQuery, Looker/LookML, Cloud Monitoring, Git
</details>

<details>
<summary><b>Cranfield University — Research Engineer (Aero Data Analytics)</b></summary>

- **Digital-Twin-style Analytics**
  - **Built:** MATLAB/Turbomatch pipeline simulating flight conditions; **~95%** parameter prediction accuracy for maintenance planning.
- **Signal Processing**
  - **Implemented:** Scattered interpolation for remote engine data → error **<1%** (Case 1) and **~3%** (Case 2).

**Tech:** MATLAB, Turbomatch, data interpolation, experiment design
</details>

---
## 📊 GitHub Statistics & Analytics

### 📈 Profile Stats
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=SanskarLoganDev&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

### 🔥 Contribution Streak
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=SanskarLoganDev&theme=tokyonight&hide_border=true)

### 💻 Most Used Languages
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SanskarLoganDev&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

### 🏆 GitHub Trophies
![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=SanskarLoganDev&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=15)

### 📊 Contribution Graph
![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=SanskarLoganDev&theme=tokyo-night&hide_border=true&area=true)

---

## 📫 Contact
- Email: **sanskar.vidyarthi102@gmail.com**  
- LinkedIn: **linkedin.com/in/sanskar-vidyarthi**  


