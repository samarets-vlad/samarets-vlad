<h1 align="center">Привіт, я Влад 👋</h1>
<h3 align="center">DevOps Engineer · Хмарна інфраструктура · AWS · Terraform · Kubernetes</h3>

<p align="center">
  <a href="mailto:vladyslav.samarets.work@gmail.com"><img src="https://img.shields.io/badge/Email-vladyslav.samarets.work%40gmail.com-blue?style=flat-square&logo=gmail"/></a>
  <img src="https://img.shields.io/badge/Location-Reutte%2C%20Austria-lightgrey?style=flat-square&logo=google-maps"/>
  <img src="https://img.shields.io/badge/Open%20to-Remote%20Only-brightgreen?style=flat-square"/>
</p>

---

## 🚀 Про мене

DevOps Engineer з практичним досвідом проєктування, автоматизації та підтримки хмарної інфраструктури на AWS.  
Працюю з невеликими командами та стартапами як незалежний контрактор — від zero‑to‑prod інфраструктури до повністю автоматизованих CI/CD пайплайнів.

- 🏗️ Infrastructure as Code з **Terraform** (модулі, remote state, multi‑env workspaces)
- ⚙️ Конфігурація та автоматизація з **Ansible** (ідемпотентні playbookʼи, ролі)
- 🐳 Контейнеризація: **Docker**, **Docker Compose**, **Kubernetes (k8s)**, **Helm**
- 🔁 CI/CD: **GitHub Actions**, **GitLab CI** — build → test → push → deploy
- 📊 Спостережуваність: **Prometheus**, **Grafana**, **Loki**, **Alertmanager**
- ☁️ AWS: EC2, S3, RDS, Lambda, Route53, ECR, ALB, CloudFront, VPC, IAM, CloudWatch

---

## 🛠️ Технології

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

## 📂 Портфоліо

| Проєкт | Стек | Опис |
|---|---|---|
| 🐘 [postgres-cluster](https://github.com/samarets-vlad/postgres-cluster) | PostgreSQL 16 · Patroni · etcd · pgBouncer · HAProxy · WAL-G · MinIO · Ansible | Production‑grade HA кластер PostgreSQL: auto‑failover, синхронна реплікація (zero data loss), R/W split, пулінг зʼєднань, WAL‑архівація + щоденні бекапи в S3‑сумісне сховище, моніторинг на Prometheus/Grafana |
| 🏗️ [aws-terraform-infra](https://github.com/samarets-vlad/aws-terraform-infra) | Terraform · AWS · VPC · ALB · EC2 · RDS · S3 | AWS інфраструктура з багатооточеневою підтримкою: VPC, публічні/приватні підмережі, ALB, EC2, RDS, S3, remote state на S3+DynamoDB, тести через tflint/tfsec |
| ⚙️ [ansible-server-setup](https://github.com/samarets-vlad/ansible-server-setup) | Ansible · Nginx · Docker · Linux · TLS | Ідемпотентне розгортання серверів: Docker CE, Nginx reverse proxy, self‑signed або Let’s Encrypt TLS, деплой застосунків через Docker Compose |
| 🔁 [docker-ecr-ec2-pipeline](https://github.com/samarets-vlad/docker-ecr-ec2-pipeline) | GitHub Actions · Docker · AWS ECR · EC2 | Production CI/CD пайплайн: multi‑stage Docker build → ECR → деплой на EC2 через AWS SSM та GitHub OIDC (без постійних SSH ключів) |
| 📊 [monitoring-stack](https://github.com/samarets-vlad/monitoring-stack) | Prometheus · Grafana · Alertmanager · Ansible · Docker | Повний стек моніторингу та алертингу, розгорнутий Ansible + Docker Compose, з Nginx reverse proxy та TLS |
| ☸️ [k8s-helm-app](https://github.com/samarets-vlad/k8s-helm-app) | k3s · Helm · Traefik · cert-manager · MySQL · Loki | Full‑stack Todo застосунок на k3s: 6 Helm chartʼів, Let’s Encrypt TLS, щоденні бекапи БД, моніторинг Prometheus + Loki |
| λ [serverless-aws-pipeline](https://github.com/samarets-vlad/serverless-aws-pipeline) | Terraform · Lambda · API Gateway · DynamoDB · S3 · CloudFront | Повністю serverless TODO API: інфраструктура на Terraform + деплой через GitHub Actions, CloudWatch дашборд і алерти для Lambda/API/DynamoDB |

---

## 📜 Сертифікації

- 🎓 **DevOps & Cloud Infrastructure** — FoxMinded Mentorship Programme, 2026  
  *(AWS · Terraform · Ansible · Kubernetes · CI/CD · Docker · Prometheus · Grafana · Loki)*

---

## 🎓 Освіта

- **Магістр** — Кібербезпека та захист даних · НУРЕ, 2024–2025
- **Бакалавр** — Кібербезпека · НУРЕ, 2020–2024

---

## 🌍 Мови

- 🇺🇦 Українська — рідна  
- 🇷🇺 Російська — вільно  
- 🇬🇧 Англійська — B2
