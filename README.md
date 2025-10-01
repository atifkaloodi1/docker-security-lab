# Docker Container Security Lab

## 🛡️ Overview
This project demonstrates how to scan and secure Docker containers using Trivy and Docker Bench for Security. The vulnerable app used is OWASP Juice Shop.

## 🔧 Tools Used
- Docker & Docker Compose
- Trivy
- Docker Bench for Security
- GitHub Actions (CI/CD)

## 🚀 Setup
```bash
docker-compose up -d
trivy image bkimminich/juice-shop
bash docker-bench-security.sh
