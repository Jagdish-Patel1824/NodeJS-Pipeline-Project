# Full DevOps CI/CD Pipeline for NodeJS Application on AWS

## 📌 Project Overview

This project demonstrates a complete end-to-end DevOps CI/CD pipeline for deploying a NodeJS application on AWS using Terraform, Ansible, Jenkins, Docker, K3s Kubernetes, Prometheus, and Grafana.

The pipeline automates infrastructure provisioning, server configuration, containerization, Kubernetes deployment, monitoring setup, and dashboard visualization in a real cloud environment.

---

## 🚀 Tech Stack

### Cloud Platform
- AWS EC2

### Infrastructure & Automation
- Terraform
- Ansible
- Dynamic Inventory

### CI/CD Tools
- Jenkins
- GitHub Webhooks

### Containerization & Orchestration
- Docker
- Kubernetes (K3s)

### Monitoring & Observability
- Prometheus
- Grafana
- ServiceMonitor

### Application Stack
- NodeJS
- ExpressJS

---

## ⚙️ Features

- Automated AWS infrastructure provisioning
- Automated server configuration using Ansible
- Dynamic inventory integration
- Jenkins CI/CD pipeline automation
- Docker image build and push automation
- Kubernetes deployment using K3s
- Prometheus metrics scraping
- Grafana dashboard visualization
- Real-time monitoring integration
- Fully cloud-hosted deployment
- End-to-end automation workflow

---

## 🏗️ Architecture Flow

GitHub → Jenkins → Terraform → Ansible → Docker → K3s Kubernetes → Prometheus → Grafana

---

## 📂 Project Structure

```bash
terraform/
ansible/
jenkins-pipeline
kubernetes/
monitoring/
```

---

## ☸️ Kubernetes Deployment

- NodeJS application deployed on K3s cluster
- Kubernetes Deployment and Service manifests used
- NodePort service exposure configured
- Rolling deployment support enabled

---

## 📊 Monitoring & Observability

### Prometheus
- Metrics scraping enabled using ServiceMonitor
- Application metrics exposed using prom-client
- Kubernetes monitoring configured

### Grafana
- Dashboard visualization configured
- Dashboard provisioning using ConfigMap
- Real-time metrics monitoring enabled

---

## 🐛 Problems Solved During Development

- Prometheus scrape target not detected
- ServiceMonitor configuration issue
- Problem in Injecting dashborad.json to Grafana dashboard (Classic VS V2 Schema).
- Container restart crash debugging

---

## 📄 Detailed Documentation

See `Project_Report.pdf` for:
- Architecture diagrams
- Kubernetes deployment screenshots
- Prometheus targets
- Grafana dashboards

---

## ✅ Final Outcome

Successfully built and deployed a fully automated DevOps pipeline for a NodeJS application on AWS with:

- Infrastructure as Code
- CI/CD automation
- Kubernetes orchestration
- Real-time monitoring
- Dashboard visualization
- End-to-end cloud deployment1
