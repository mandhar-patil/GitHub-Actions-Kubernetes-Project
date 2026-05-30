# GitHub-Actions-Kubernetes-Project


# 🚀 3-Tier Application Deployment using GitHub Actions, ArgoCD, and Amazon EKS

## 📌 Project Overview

This project demonstrates the deployment of a **3-Tier Application** on **Amazon EKS (Elastic Kubernetes Service)** using modern DevOps practices.

The deployment pipeline follows a **GitOps-based CI/CD workflow**:

- **Continuous Integration (CI)** using GitHub Actions
- **Containerization** using Docker
- **Image Registry** using Docker Hub
- **Continuous Deployment (CD)** using ArgoCD
- **Container Orchestration** using Amazon EKS

---

## 🏗️ Architecture

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
GitHub Actions (CI)
    │
    ├── Checkout Source Code
    ├── Build Docker Image
    ├── Push Image to Docker Hub
    │
    ▼
Git Repository (Manifests)
    │
    ▼
ArgoCD
    │
    ▼
Amazon EKS Cluster
    │
    ▼
3-Tier Application
