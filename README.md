## Hi there 👋

# I’m Sanskar Vidyarthi 👋
*M.Eng. Software Engineering @ University of Maryland (May 2026)*  
**Software Engineer — Systems • Networking • Cloud/Observability**

- I build back-end services, security automation, and network tooling.  
- Comfortable across **Python** and **C/C++** on **Linux/Windows**, with cloud infra in **AWS/GCP**, **Terraform**, **Docker**, and **GitHub Actions**.  
- Interested in **network test/observability**, **embedded basics (ESP32/FreeRTOS)**, and **production reliability**.

---

## 🔎 Highlights (results, not just responsibilities)
- Shipped **20+ REST APIs** (Python/Flask), fixed **40+ defects**, and wrote **80+ PyTest** cases → higher reliability & maintainability.  
- Built a serverless **CVE alerting** workflow (AWS Lambda/EventBridge/PostgreSQL) with idempotency → **3-hour detection SLA** and zero duplicate notifications.  
- Deployed a GitHub App–based **secret scanner** (Lambda/SQS/Fargate/Gitleaks) with PR checks → **~60% reduction** in credential exposure; **~50%** less manual review.  
- Provisioned **EKS via Terraform**, deployed **OpenTelemetry** with Helm, added CI/CD with rollback and **Prometheus/Alertmanager → Slack** → faster, auditable releases.

---

## 🛠️ Tech Stack (short list for screeners)
**Languages:** Python, C, C++  
**Systems & Networking:** Linux, Windows, TCP/UDP sockets, libpcap, Wireshark  
**Cloud & IaC:** AWS, GCP, Terraform, Docker, GitHub Actions, Kubernetes (EKS), Helm  
**Observability:** OpenTelemetry, Prometheus, Grafana, Jaeger  
**Back-End & Data:** Flask, FastAPI (familiar), PostgreSQL/MySQL, BigQuery  
**Embedded (familiar):** ESP32/FreeRTOS, CMake

> Full certifications: GCP **Professional Cloud Architect**, **Associate Cloud Engineer**, **AZ-900** Azure Fundamentals

---

## 📦 Selected Projects (pin these repos)
### NetScope — C++/libpcap Packet Analyzer (Windows/WSL)
- **Built** a packet analyzer decoding Ethernet/IPv4/TCP/UDP and surfacing “top talkers/flows” to pinpoint bandwidth hogs and flaky services.  
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

> 👉 **Tip:** Pin these repositories on your profile for quick recruiter access.

---

## 🧭 Experience in Brief
**CBTS — Software Developer Intern**  
Security pipelines (CVE alerting, secret scanning), CI policy gates, structured logs/metrics, runbooks.  

**Accenture — Software Developer I**  
API design & implementation at scale (20+ REST APIs), testing (80+ PyTest), cloud releases (Docker + Terraform), monitoring/dashboards.

**Cranfield University — Research Engineer (Aero Data Analytics Project)**  
MATLAB/Turbomatch simulations; ~95% parameter prediction accuracy; digital-twin style analysis.

---

## 📫 Contact
- Email: **sanskar.vidyarthi102@gmail.com**  
- LinkedIn: **linkedin.com/in/sanskar-vidyarthi-6b04041ab**  
- Location: **Hyattsville, MD** (open to relocation)

---

### How this page helps recruiters
- **Metrics first**: outcomes and scale (APIs shipped, defects fixed, SLAs met).  
- **Targeted stack**: Python + C/C++, systems/networking, cloud/observability, CI/CD.  
- **Pinned work**: direct links to code that demonstrates shipping & reliability.

