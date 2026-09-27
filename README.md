# ☸️ Kubernetes Microservices Deployment

A production-ready Kubernetes orchestration manifest featuring High Availability (HA) replicas, automated self-healing health probes, and internal service load balancing.

## 🚀 Architecture & Features
* **Multi-Replica Deployment:** Runs 3 concurrent container pods to guarantee zero downtime and fault tolerance.
* **Self-Healing Probes:** Configured with liveness and readiness probes to automatically restart unhealthy containers and manage traffic routing.
* **Resource Governance:** Enforces strict CPU and memory requests/limits to prevent resource starvation in shared cluster environments.
* **Internal Networking:** Exposes pods via a stable ClusterIP service mapping port 80 to container port 8080.

## 🛠️ Tech Stack
* **Orchestration:** Kubernetes (K8s)
* **Container Runtime:** Docker
* **Tooling:** `kubectl`, Minikube / Docker Desktop K8s

## 📦 Deployment Guide

### 1. Clone the Repository
```bash
git clone [https://github.com/chaituupasi3-wq/kubernetes-microservices-deployment.git](https://github.com/chaituupasi3-wq/kubernetes-microservices-deployment.git)
cd kubernetes-microservices-deployment
