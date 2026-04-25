# 🚀 Jenkins Shared Library

## 📌 Repository Description

Production-ready Jenkins Shared Library for reusable CI/CD pipelines supporting Java, Node.js, and Python applications with automated build, test, Docker image creation, EKS deployment, and standardized DevOps workflows.

---

## 📌 Project Overview

This repository contains reusable Jenkins Shared Library code to standardize CI/CD pipelines across multiple applications and teams.

It helps reduce duplicate Jenkinsfile code by centralizing common pipeline logic for Java, Node.js, and Python projects with automated deployment to Amazon EKS.

---

## 🛠️ Tools & Technologies

- Jenkins
- Groovy
- Shared Libraries
- Docker
- Kubernetes
- Amazon EKS
- GitHub
- Maven
- Node.js
- Python
- CI/CD

---

## 🏗️ Pipeline Components

- Reusable Shared Library Functions
- Java Application Pipeline
- Node.js Application Pipeline
- Python Application Pipeline
- Docker Image Build
- Docker Image Push
- Kubernetes Deployment
- EKS Deployment Automation
- Environment Variables Handling
- CI/CD Standardization

---

## 📂 Repository Structure

```bash
vars/
├── EKSDeploy.groovy
├── javaEKSPipeline.groovy
├── nodeJSEKSPipeline.groovy
└── pythonEKSPipeline.groovy
```
---
## 🚀 Usage Example

@Library('jenkins-shared-library') _

javaEKSPipeline()

---

🔐 Key Features
- Reusable CI/CD Pipelines
- Centralized Jenkins Logic
- Reduced Jenkinsfile Duplication
- Java / Node.js / Python Support
- Automated Docker Build & Push
- Amazon EKS Deployment
- Standardized Pipeline Stages
- Easy Maintenance & Scalability

---

📸 Architecture Flow

Developer → GitHub → Jenkins Shared Library → Build/Test → Docker Build → EKS Deploy → Users

---

📈 Real-Time Use Cases
- Common CI/CD framework for multiple teams
- Faster onboarding of new projects
- Standardized deployments across environments
- Reduced maintenance of multiple Jenkinsfiles
- Automated Kubernetes application delivery

---

👨‍💻 Author

Surendra DevOps Engineer

⭐ If you like this project, give it a star.