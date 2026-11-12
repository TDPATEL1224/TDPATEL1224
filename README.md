<h1 align="center">Hi, I'm Tirth Patel 👋</h1>

<p align="center">
  <b>IT professional — systems, cloud infrastructure, and automation</b><br>
  Toronto, ON · Open to relocation across Canada
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tirth-patel-33827a381"><img src="https://img.shields.io/badge/LinkedIn-Tirth%20Patel-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:tirthdpatel08@gmail.com"><img src="https://img.shields.io/badge/Email-tirthdpatel08%40gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/AWS-Certified%20Cloud%20Practitioner-FF9900?logo=amazonwebservices&logoColor=white" alt="AWS Certified Cloud Practitioner">
</p>

---

I started in software development (Computer Programming diploma, Seneca Polytechnic) and moved into infrastructure through the Cloud Architecture & Administration graduate certificate. I like the operations side of IT: building systems that are documented, repeatable, and easy to support, then automating whatever people keep doing by hand.

Across the projects below I've worked on **Windows and Active Directory administration, endpoint provisioning, service-desk workflows, AWS and Azure infrastructure, Terraform, containers and Kubernetes, CI/CD, and full-stack web apps**.

## 🔨 Currently building

| Project | What it is | Status |
|---|---|---|
| **[k8s-zero-downtime-secret-rotation](https://github.com/TDPATEL1224/k8s-zero-downtime-secret-rotation)** | Rotating a database password on Kubernetes while the app keeps serving traffic, with no failed requests during the switch. Flask + MySQL, rolling updates, readiness probes. | 🚧 In progress |
| **[CloudOps Hub](https://github.com/AaronKingCloud/CloudOpsHub)** · team of 3 | Infrastructure monitoring and asset-visibility platform. I built the React dashboard, the FastAPI backend skeleton, GitHub Actions CI, and the Docker setup. | 🚧 In progress |

## ⭐ Featured projects

| Project | Area | Highlights |
|---|---|---|
| **[Service Desk Ticketing & Troubleshooting Simulator](https://github.com/TDPATEL1224/service-desk-simulator)** | IT support / ITSM | ITIL-style impact × urgency priority matrix, live SLA timers, auto-assignment, knowledge base for lockouts, Wi-Fi, Outlook, printing |
| **[Endpoint Provisioning Toolkit](https://github.com/TDPATEL1224/endpoint-provisioning-toolkit)** | Endpoint management | PowerShell + Bash new-hire setup for Windows 11 and macOS, Entra ID / M365 readiness, dry-run mode, Pester + ShellCheck in CI |
| **[IT Asset Management System](https://github.com/TDPATEL1224/IT-Asset-Management-and-Inventory-Tracking-System)** | IT operations | Full asset lifecycle, QR labels and barcode scanning, audit discrepancy detection, PostgreSQL append-only history |
| **[Two-Tier Auto-Scaling Web App with Terraform](https://github.com/TDPATEL1224/Two-tier-autoscaling-web-app-terraform)** | Infrastructure as code | Dev/Staging/Prod from reusable modules, ALB + Auto Scaling Group, TFLint + Trivy security scans on every push |
| **[Multi-Environment AWS Network with Terraform](https://github.com/TDPATEL1224/Aws-multi-env-network-terraform)** | Networking / IaC | Routable nonprod + private-only prod VPCs over VPC peering, separate state for every layer |
| **[Event-Driven Serverless Pipeline](https://github.com/TDPATEL1224/Event-Driven-Serverless-Pipeline)** | Automation / serverless | S3 upload triggers Lambda, which validates the data and writes it to DynamoDB; no servers, no polling |

<details>
<summary><b>More projects</b></summary>

**On GitHub**
- **[Resilient News Ingestion Pipeline](https://github.com/TDPATEL1224/resilient-news-ingestion-pipeline):** scheduled Lambda + EventBridge archiving API data to S3, built to prove the failure handling
- **[Flask Deploy: EC2 by Hand vs Docker](https://github.com/TDPATEL1224/flask-deploy-ec2-vs-docker):** the same app deployed manually on a Terraform-built EC2 server and as a multi-arch Docker image, then compared

**Built in Azure / AWS (no public repo)**
- **Enterprise Active Directory network on Azure:** AD DS domain, domain-joined IIS server and Windows 11 client, 3 peered VNets, Azure Bastion with zero public IPs
- **Multi-region resilient website on Azure:** Canada East + Central India, two IIS servers per region, round-robin load balancing, routing to the nearest region
- **Auto-scaling 3-tier web app on AWS:** ALB + Auto Scaling Group + RDS MySQL + EFS, load-tested from 2 to 6 instances, then self-healing after terminating every instance
- **CI/CD to Kubernetes:** GitHub Actions builds and pushes Docker images (version and commit-SHA tags) to a 3-node kubeadm cluster, then a rolling update and a rollback
- **Azure data services:** Azure SQL Database with Azure Monitor alerts, Cosmos DB for NoSQL, and storage redundancy and failover planning
- **Linux server hardening on EC2:** built entirely with AWS CLI, custom systemd service, least-privilege service account

</details>

## 🧰 Tools I've used hands-on

**Systems & support**
![Windows Server](https://img.shields.io/badge/Windows%20Server-0078D6?logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active%20Directory-0078D4?logo=microsoft&logoColor=white)
![Entra ID](https://img.shields.io/badge/Microsoft%20Entra%20ID-0078D4?logo=microsoft&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white)

**Cloud & infrastructure**
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

**Development & data**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

## 📜 Certifications & education

- AWS Certified Cloud Practitioner
- Graduate Certificate, Cloud Architecture & Administration · Seneca Polytechnic
- Diploma, Computer Programming · Seneca Polytechnic

---

<p align="center"><i>Last updated: November 2026</i></p>
