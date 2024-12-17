# DockerK8s101
# Docker and Kubernetes Research Project

This repository contains research materials and a practical demo on Docker and Kubernetes for our **Enterprise Applications Project**. The project aims to provide an understanding of these technologies, their features, and how they can be applied in modern application development.

---

## Table of Contents
- [Introduction](#introduction)
- [What is Docker?](#what-is-docker)
- [What is Kubernetes?](#what-is-kubernetes)
- [Demo Overview](#demo-overview)
- [Demo Setup Instructions](#demo-setup-instructions)
- [Use Cases](#use-cases)
- [Strengths and Weaknesses](#strengths-and-weaknesses)
- [Contributors](#contributors)

---

## Introduction
Docker and Kubernetes are widely-used tools for containerization and orchestration in modern application development. This project explores their capabilities and provides a hands-on demo to illustrate their usage.

---

## What is Docker?
Docker is a platform designed to simplify the process of building, deploying, and running applications in containers. Containers package an application and its dependencies, ensuring consistency across environments.

---

## What is Kubernetes?
Kubernetes (K8s) is an open-source platform for automating the deployment, scaling, and management of containerized applications.

---

## Demo Overview
Our demo illustrates the following:
- **Docker**: Packaging a simple web application into a container.
- **Kubernetes**: Deploying and managing the containerized application in a Kubernetes cluster.

---

## Demo Setup Instructions

### Prerequisites
- Install [Docker](https://www.docker.com/products/docker-desktop).
- Install [Kubernetes](https://kubernetes.io/docs/tasks/tools/) (Minikube or a cloud provider).
- Install [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/).

---

### Step 1: Docker Demo
1. Clone this repository:
   ```bash
   git clone <repository-url>
   
2. cd demo-app-post
3. docker build -t demo-app-post 
4.docker run -p 8080:8080 demo-app-post
5. Open your browser and navigate to http://localhost:8080 to view the running application.
   
### Step 2: Kubernetes Demo
 1.cd ../springboot-app1

2. kubectl apply -f k8s-deployment.yaml
   
3. kubectl get pods
   
4. kubectl expose deployment springboot-app1 --type=LoadBalancer --name=springboot-app1-service

5. minikube service springboot-app1





