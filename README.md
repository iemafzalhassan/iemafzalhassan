<div align="center">

# Afzal Hassan
### **Platform & Reliability Engineer** | **Cloud-Native & SRE Architecture**
**Operating Air-Gapped Banking Platforms** • **Autonomous AI for Observability** • **Tech Community Builder**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Afzal_Hassan-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iemafzalhassan/)
[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio.iemafzalhassan.tech-000000?style=flat-square&logo=google-chrome&logoColor=white)](https://portfolio.iemafzalhassan.tech)
[![GitHub](https://img.shields.io/badge/GitHub-iemafzalhassan-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/iemafzalhassan)
[![Email](https://img.shields.io/badge/Email-iemafzalhassan%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:iemafzalhassan@gmail.com)

---

> *"Building deterministic, resilient distributed systems where security and observability are foundational invariants."*

</div>

---

## ⚡ Executive Summary

Platform & DevOps Engineer at **Sunfire Technologies** (deployed on-site with **Yubi**), operating an enterprise collections platform for a Tier-1 Indian public-sector bank across air-gapped **Red Hat OpenShift** clusters (zero internet egress). 

- **Core Engineering:** Air-gapped release engineering, deterministic disaster recovery drills (RTO/RPO compliance), zero-trust network policies (OVN-Kubernetes), and enterprise IAM (Keycloak 26 OIDC).
- **AI + Observability:** Co-organizer of **Grafana & Friends Mumbai** and creator of **OutagePilot** (an autonomous multi-agent SRE triage engine powered by Go and Gemini).
- **Community:** Core Team Member at **Cloud Native Mumbai** (500+ engineers) and co-builder of **Merge & Rise**.

---

## 🚀 Flagship Architecture & Engineering Projects

| Project | Domain / Architecture | Highlights & Core Stack | Repository |
| :--- | :--- | :--- | :---: |
| **[OutagePilot](https://github.com/iemafzalhassan/OutagePilot)** | **Autonomous AI SRE Platform** | Lightweight in-cluster Go daemons capturing real-time K8s anomalies (`OOMKilled`, `CrashLoopBackOff`); autonomous ReAct triage loop using Google Gemini to formulate remediation runbooks and healing patches. | [Code](https://github.com/iemafzalhassan/OutagePilot) |
| **EdgeOps** | **Hybrid Multi-Arch Zero-Trust Mesh** | Persistent hybrid K8s cluster (ARM64 Apple Silicon + x86_64) interconnected via Flannel VXLAN bound to Tailscale WireGuard (`tailscale0`). Zero inbound open ports via Cloudflare Tunnels, Keycloak 26 OIDC, and CloudNativePG HA. | `Private / Homelab` |
| **[terraform-cluster](https://github.com/iemafzalhassan/terraform-cluster)** | **Production Amazon EKS Auto Mode** | Declarative multi-AZ AWS VPC architecture with dynamic node provisioning via Karpenter, IRSA least-privilege scoping, KMS envelope encryption, and metrics server automation. | [Code](https://github.com/iemafzalhassan/terraform-cluster) |
| **Kube-Telemetry-Stage** | **Cloud-Native Observability & Gateway API** | Modern Azure AKS deployment migrating legacy Ingress to Kubernetes Gateway API (GA v1.5) via Traefik v3 HTTPRoute splitting, Azure Workload Identity Federation, and ArgoCD GitOps bootstrapping. | [Architecture](https://portfolio.iemafzalhassan.tech) |
| **[Excalidraw Integration](https://github.com/iemafzalhassan)** | **Open-Source Multi-Board Engine** | Engineered Google Drive-backed multi-board persistence and containerized Docker distribution for self-hosted collaborative whiteboarding. | [PR / Fork](https://github.com/iemafzalhassan) |

---

## 🛠 Technical Invariants & Stack

```
PLATFORM & ORCHESTRATION    ▸ Kubernetes • Red Hat OpenShift • Amazon EKS • Azure AKS • Docker
INFRASTRUCTURE AS CODE      ▸ Terraform • OpenTofu • Terragrunt • Helm • Bash • Linux (RHEL, Debian)
GITOPS & CONTINUOUS FLOW    ▸ ArgoCD (App-of-Apps) • GitHub Actions • GitLab CI • Jenkins (ephemeral JNLP)
OBSERVABILITY & RELIABILITY ▸ Grafana • Prometheus • Loki • OpenTelemetry • Traefik Gateway API
SECURITY & ZERO-TRUST       ▸ Keycloak (OIDC/OAuth2) • External Secrets Operator (ESO) • OpenBao / Vault • Tailscale
PROGRAMMING & SYSTEMS       ▸ Go (Golang) • Python • Bash / Shell Scripting • TypeScript / Node.js
```

---

## 📜 Verified Credentials

<p align="left">
  <img src="https://img.shields.io/badge/Certified%20Kubernetes%20Administrator-(CKA)-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="CKA" />
  <img src="https://img.shields.io/badge/GitLab-Solutions%20Architect%20Verified%20Associate-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab SA" />
  <img src="https://img.shields.io/badge/Linux%20Foundation-LFS169%20Introduction%20to%20GitOps-003B5C?style=for-the-badge&logo=linuxfoundation&logoColor=white" alt="GitOps" />
  <img src="https://img.shields.io/badge/GitHub-Foundations%20Certified-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Foundations" />
</p>

---

## 🎙 Talks & Community Leadership

- **Co-Organizer — [Grafana & Friends Mumbai](https://www.linkedin.com/company/grafana-user-group-mumbai/)**: Curating technical sessions on Prometheus, Loki, OpenTelemetry, and speaking on *"From Alert to Action with Grafana MCP and AI"* alongside Simon Prickett (Grafana Labs).
- **Core Team Member — [Cloud Native Mumbai](https://www.linkedin.com/company/cloudnativemumbai/)**: Organizing in-person CNCF meetups, workshops, and CFPs for a vibrant community of 500+ cloud-native engineers.
- **Co-Builder — Merge and Rise**: Driving DEI and technical empowerment initiatives for women in cloud-native and AI engineering.
- **Academic Outreach**: Guest technical speaker at ITM Skills University on container runtimes, Kubernetes architecture, and open-source contribution pathways.

---

## 📈 Activity & Contribution Velocity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=iemafzalhassan&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" width="49%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iemafzalhassan&theme=tokyonight&hide_border=true&layout=compact&langs_count=6" width="45%" />
</div>

<br/>

<div align="center">
  <sub>Designed with precision. Committed to high-availability and zero downtime.</sub>
</div>
