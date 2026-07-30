# 🚀 ProFinFly AI

![Python](https://img.shields.io/badge/Python-3.12-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Framework-009688)
![React](https://img.shields.io/badge/React-18-61DAFB)
![Docker](https://img.shields.io/badge/Docker-Container-blue)
![Jenkins](https://img.shields.io/badge/Jenkins-CI-red)
![AWS](https://img.shields.io/badge/AWS-Cloud-orange)

> AI-powered financial intelligence platform that provides stock analysis, AI-powered financial insights, portfolio management, and real-time market intelligence using React, FastAPI, PostgreSQL, Docker, Jenkins CI/CD, Nginx, and AWS.


## 📑 Table of Contents

## 📌 Project Overview
ProFinFly AI is a full-stack AI-powered financial intelligence platform designed to help users analyze stocks, manage portfolios, and access AI-driven market insights through a modern web interface.

The application follows a production-style architecture using React for the frontend, FastAPI for backend APIs, PostgreSQL for data storage, Docker for containerization, Jenkins for CI/CD automation, Nginx as a reverse proxy, and AWS for cloud deployment.

This project demonstrates end-to-end DevOps practices, including application containerization, automated deployment pipelines, cloud infrastructure management, and production-ready application deployment.

## ✨ Features
- 📈 AI-powered stock analysis
- 🤖 Intelligent financial assistant
- 💼 Portfolio management
- 📊 Interactive financial dashboard
- 🔐 Secure REST APIs with FastAPI
- 🐳 Dockerized application deployment
- 🔄 Automated CI/CD pipeline using Jenkins
- ☁️ AWS cloud deployment
- 🌐 Nginx reverse proxy configuration
- 🗄️ PostgreSQL database integration

## 🏗️ Architecture

```text
                        Internet
                            │
                            ▼
                    Nginx Reverse Proxy
                            │
            ┌───────────────┴───────────────┐
            ▼                               ▼
     React Frontend                 FastAPI Backend
                                            │
                                            ▼
                                     PostgreSQL Database
```

### Architecture Workflow

1. User accesses the application through the browser.
2. Nginx serves the React frontend and acts as a reverse proxy.
3. API requests are forwarded to the FastAPI backend.
4. FastAPI processes business logic.
5. PostgreSQL stores application and portfolio data.
6. Docker containers package all services.
7. Jenkins automates build and deployment.
8. AWS EC2 hosts the production application.

## 🛠️ Technology Stack
| Category | Technologies |
|----------|--------------|
| Frontend | React, Vite, HTML, CSS, JavaScript |
| Backend | Python, FastAPI |
| Database | PostgreSQL |
| DevOps | Docker, Docker Compose, Jenkins |
| Web Server | Nginx |
| Cloud | AWS EC2 |
| Version Control | Git, GitHub |

## 📂 Project Structure

```text
ProFinFly-AI/
│
├── backend/                # FastAPI backend
├── src/                    # React frontend source
├── public/                 # Static assets
├── docs/                   # Project documentation
├── Architecture/           # Architecture diagrams
├── Screenshots/            # Project screenshots
│
├── Dockerfile.frontend
├── docker-compose.yml
├── Jenkinsfile
├── nginx.conf
├── package.json
├── README.md
└── .gitignore
```

## 🐳 Docker Deployment

The application is containerized using Docker to provide a consistent deployment environment across development and production.

### Components

- React Frontend
- FastAPI Backend
- PostgreSQL Database
- Nginx Reverse Proxy

Docker Compose orchestrates all services and simplifies local development and deployment.

## 🔄 Jenkins CI/CD Pipeline

The project uses Jenkins to automate the deployment workflow.

### Pipeline Stages

- Clone Repository
- Install Dependencies
- Build Frontend
- Build Docker Images
- Deploy Containers
- Verify Deployment

The CI/CD pipeline ensures consistent and repeatable deployments with minimal manual intervention.
## ☁️ AWS Deployment

The application is deployed on AWS EC2 using Docker containers.

### AWS Services Used

- Amazon EC2
- Security Groups
- Elastic IP
- Docker
- Nginx
- Jenkins

This deployment demonstrates production-style cloud hosting and infrastructure management.

## 📸 Screenshots

Screenshots will be added after deployment.

- Application Dashboard
- AI Assistant
- Docker Containers
- Jenkins Pipeline
- AWS EC2 Instance
- Nginx Configuration

## 📚 Documentation

Detailed guides are available in the `docs` directory.

- Installation Guide
- Deployment Guide
- Troubleshooting Guide

## 🚀 Future Improvements

- Kubernetes deployment
- Terraform infrastructure provisioning
- GitHub Actions support
- Monitoring with Prometheus & Grafana
- AWS ECS/EKS deployment
- AI-powered portfolio recommendations
## 👨‍💻 Author

**Naveen Reddy**

Cloud | DevOps | AI Deployment Enthusiast

GitHub: https://github.com/reddynaveen0106-boop
