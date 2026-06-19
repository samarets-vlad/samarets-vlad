<h1 align="center">Hi, I'm Vlad 👋</h1>
<h3 align="center">DevOps Engineer · Cloud Infrastructure · AWS · Terraform · Kubernetes</h3>

<p align="center">
  <a href="mailto:vladyslav.samarets.work@gmail.com"><img src="https://img.shields.io/badge/Email-vladyslav.samarets.work%40gmail.com-blue?style=flat-square&logo=gmail"/></a>
  <img src="https://img.shields.io/badge/Location-Vienna%2C%20Austria-lightgrey?style=flat-square&logo=google-maps"/>
  <img src="https://img.shields.io/badge/Open%20to-Remote%20Only-brightgreen?style=flat-square"/>
</p>

---

## 🚀 About Me

DevOps / Infrastructure Engineer focused on reliable, reproducible infrastructure and pipelines on AWS and Linux.  
I work with small teams and startups as an independent contractor: from zero‑to‑production infra to CI/CD and observability.

- 🏗️ Infrastructure as Code with **Terraform** (modules, remote state, multi‑env setups, tflint/tfsec)
- ⚙️ Configuration management with **Ansible** (idempotent roles, HA clusters, monitoring stacks)
- 🐳 Containerization: **Docker**, **Docker Compose**, **Kubernetes (k8s)**, **Helm**
- 🔁 CI/CD: **GitHub Actions**, **GitLab CI** — build → test → scan → deploy (including OIDC, SSM‑based deploys)
- 📊 Observability: **Prometheus**, **Grafana**, **Loki**, **Alertmanager**
- ☁️ AWS: EC2, S3, RDS, Lambda, Route53, ECR, ALB, CloudFront, VPC, IAM, CloudWatch

Self‑taught via real projects, documentation, and labs — no formal CS degree.

---

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-%23326CE5.svg?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Helm-%230F1689.svg?style=for-the-badge&logo=helm&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitLab%20CI-%23FC6D26.svg?style=for-the-badge&logo=gitlab&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-%23E6522C.svg?style=for-the-badge&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bash-%234EAA25.svg?style=for-the-badge&logo=gnubash&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white"/>
</p>

---

## 📂 Portfolio Projects

| Project | Stack | Description |
|---|---|---|
| 🐘 [postgres-cluster](https://github.com/samarets-vlad/postgres-cluster) | PostgreSQL 16 · Patroni · etcd · pgBouncer · HAProxy · WAL-G · MinIO · Ansible | Production-style PostgreSQL HA lab: auto‑failover, synchronous replication (zero data loss), R/W split, connection pooling, WAL archiving + scheduled backups to S3‑compatible storage, full monitoring with Prometheus/Grafana |
| 🏗️ [aws-terraform-infra](https://github.com/samarets-vlad/aws-terraform-infra) | Terraform · AWS · VPC · ALB · EC2 · RDS · S3 | Multi‑environment AWS foundation: VPC, public/private subnets, ALB, EC2 ASG, RDS, S3 with remote state (S3+DynamoDB) and static analysis (tflint/tfsec) |
| ⚙️ [ansible-server-setup](https://github.com/samarets-vlad/ansible-server-setup) | Ansible · Nginx · Docker · Linux · TLS | Idempotent server provisioning: Docker CE, Nginx reverse proxy, self‑signed or Let’s Encrypt TLS, app deploy via docker compose |
| 🔁 [docker-ecr-ec2-pipeline](https://github.com/samarets-vlad/docker-ecr-ec2-pipeline) | GitHub Actions · Docker · AWS ECR · EC2 | CI/CD pipeline: multi‑stage Docker build → ECR → deploy to EC2 через AWS SSM (без SSH ключів) з GitHub OIDC для доступу до AWS |
| 📊 [monitoring-stack](https://github.com/samarets-vlad/monitoring-stack) | Prometheus · Grafana · Alertmanager · Ansible · Docker | Prometheus + Grafana + Alertmanager + exporters, розгорнуті Ansible + Docker Compose, з Nginx reverse proxy та TLS |
| ☸️ [k8s-helm-app](https://github.com/samarets-vlad/k8s-helm-app) | k3s · Helm · Traefik · cert-manager · MySQL · Loki | Full‑stack Todo app on k3s: 6 Helm charts, Traefik ingress, Let’s Encrypt TLS, daily DB backups (CronJob+PVC), Prometheus + Loki monitoring |
| λ [serverless-aws-pipeline](https://github.com/samarets-vlad/serverless-aws-pipeline) | Terraform · Lambda · API Gateway · DynamoDB · S3 · CloudFront | Serverless TODO API: Terraform‑provisioned infra + GitHub Actions deployment, CloudWatch dashboard and alarms for Lambda/API/DynamoDB |

---

## 🧪 How I Work

- Prefer **IaC‑first** approach — everything reproducible from code
- Start from **minimal, secure defaults**, then add features
- Document decisions with `docs/architecture.md` and `docs/decisions.md` where it makes sense
- Use **linters and security scanners** (tflint, tfsec, ansible‑lint, trivy) in CI

---

## 🌍 Languages

- 🇺🇦 Ukrainian — Native  
- 🇷🇺 Russian — Fluent  
- 🇬🇧 English — B1–B2 (actively improving for professional use)
