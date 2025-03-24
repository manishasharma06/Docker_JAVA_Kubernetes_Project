# Docker Java Kubernetes Project

This project demonstrates how to containerize a Java application using Docker and deploy it on Kubernetes. It serves as a practical guide to understanding the complete lifecycle of a microservice—from development and containerization to orchestration.

## 📦 Project Overview

This is a simplified version of a Java shopping application. It consists of:

- A sample Java backend service
- Dockerfile for containerizing the service
- Kubernetes YAML files for deploying to a K8s cluster

## 🚀 Getting Started

### Prerequisites

- Docker
- Kubernetes cluster (local with Minikube or remote)
- kubectl
- Java 11+

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/docker-Java-kubernetes-project.git
cd docker-Java-kubernetes-project

2. Build the Docker Image
docker build -t java-shopping-app .

3. Run the Docker Container Locally
docker run -p 8080:8080 java-shopping-app
Open your browser and go to: http://localhost:8080

4. Deploy to Kubernetes
kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/service.yaml
Check the status:

kubectl get pods
kubectl get services
Access the app using the service IP or NodePort.


📁 Project Structure
.
├── Dockerfile
├── k8s/
│   ├── deployment.yaml
│   └── service.yaml
├── src/
│   └── main/...
├── images/
│   └── working-output.png
└── README.md
