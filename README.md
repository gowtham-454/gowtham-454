# 👋 Hello, I'm **Gowtham Kadiyam**!

**Platform Engineer | 4 + Yrs Exp | Cloud Pak for Data (CP4D) @ IBM Software Labs **
*Architecting Scalable, Ephemeral Infrastructure for Data & AI Teams.*

---

## 🚀 Professional Mission
I specialize in managing the high-scale infrastructure lifecycle of **Cloud Pak for Data (CP4D)**. My core responsibility is ensuring the reliability, scalability, and "freshness" of the **Internal Developer Platform (IDP)**, managing **70+ microservices** across a distributed fleet of **10+ OpenShift clusters** on a daily basis.

---

## 🏗️ Daily Platform Operations (The "Main" Job)

My day-to-day focus is on **Infrastructure Reliability** and **Environment Orchestration** at scale:

* **Ephemeral Cluster Lifecycle Management:** I am responsible for the daily "Fresh Provisioning" of our infrastructure. Using the **Fyre API**, I orchestrate the creation of 10+ new OpenShift clusters every morning and ensure their decommissioning at EOD to optimize resource utilization and maintain zero-drift environments.
* **Scale Management (70+ Services):** I manage the deployment and health of 60-70+ microservices daily. This involves complex dependency management and ensuring all services are correctly configured and running across the distributed cluster fleet.
* **GPU Infrastructure Stewardship:** I manage specialized **GPU-attached clusters** dedicated to AI/ML workloads. This includes performing daily deep-cleans and state-reconciliation to ensure these high-value resources are "like-new" for every test cycle.
* **Self-Service Enablement (The Paved Road):** I maintain the **Golden Path** pipelines that allow 50+ developers to trigger their own cluster builds. By providing a parameterized interface (CPU, RAM, Storage), I eliminate the need for manual infrastructure tickets.
* **GitOps & Consistency:** I utilize **ArgoCD** as the source of truth to synchronize application states across the fleet, resolving any configuration drift in real-time to ensure production-parity.
* **Stakeholder Reporting:** I act as the bridge between infrastructure and product management, providing automated "Go/No-Go" signals for the CP4D product suite based on daily BVT (Build Verification Testing) outcomes.

---

## 🛠️ Internal Tooling & Automation (Supporting the Mission)

To support the scale of my daily operations, I have developed specialized automation tools:

* **Intelligent Diagnostic Engine (Python + Bash):** A diagnostic suite that scans the 10+ clusters for "Bad Pods," automatically extracts logs/descriptions, and audits Helm chart versions—reducing manual troubleshooting time by 90%.
* **Closed-Loop Incident Automation:** An event-driven system that automatically **creates and updates GitHub Issues** when BVT jobs fail, ensuring developers receive instant, contextual feedback (logs/metadata) without human intervention.
* **ChatOps Integration:** A Slack-based reporting bot that fetches real-time cluster telemetry and broadcasts high-fidelity status reports to manager-level stakeholders.

---

## 🛠️ Technical Ecosystem

| Category | Tools & Technologies |
| :--- | :--- |
| **Platforms** | Red Hat OpenShift, Kubernetes (EKS/Local), IBM Fyre |
| **GitOps & CI/CD** | **ArgoCD**, Jenkins, GitHub Actions, GitLab CI |
| **Infrastructure** | Terraform, Ansible, Crossplane, Helm Charts |
| **Languages** | Python (Automation), Bash, SQL |
| **Observability** | Prometheus, Grafana, ELK, Slack ChatOps |
| **Cloud** | AWS (EC2, S3, IAM, RDS, Lambda, VPC, Cloudfront), IBM Cloud |

---

## 📫 Connect with Me
- 📧 **Email:** [kadiyam.gj@gmail.com](mailto:kadiyam.gj@gmail.com)
- 💼 **LinkedIn:** [linkedin.com/in/gowtham-kadiyam](https://www.linkedin.com/in/gowtham-kadiyam)
- 📞 **Phone:** +91 9177847988

---
*“Platform Engineering isn’t about building infrastructure; it’s about building a product for engineers.”*
