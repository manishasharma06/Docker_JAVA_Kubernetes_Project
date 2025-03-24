# Java App Deployment with Docker & Kubernetes

### Overview
This project demonstrates containerizing a Java-based application and deploying it using Kubernetes. It showcases modern DevOps practices like container orchestration and environment scaling.

### Features
- Dockerized Java application
- Kubernetes deployment with YAML configs
- Health checks and rolling updates
- Scalable and fault-tolerant architecture

### Tech Stack
- Java
- Docker
- Kubernetes
- Spring Boot
- Maven

### What I Learned
- Dockerfile creation and optimization
- K8s concepts like pods, deployments, services
- YAML configuration for Kubernetes resources
- Monitoring and debugging using `kubectl`

### 📂 Run Locally
```bash
docker build -t java-k8s-app .
docker run -p 8080:8080 java-k8s-app
