# Kubernetes-from-Scratch 🚀

> A hands-on journey from Linux fundamentals to advanced Kubernetes operations.  
> Practical labs, exercises, and CKA-level preparation documented step-by-step.

---

## 🏆 Objective

This repository documents my **complete Kubernetes journey**, starting from **zero** to a **production-ready understanding** of Kubernetes and container orchestration.  
It is designed for:

- Learning Kubernetes fundamentals and architecture
- Practicing **real-world container and cluster management**
- Preparing for the **Certified Kubernetes Administrator (CKA) exam**
- Showcasing practical labs for portfolio or interviews

---

## 📂 Repository Structure

Each folder represents a **day or topic** with practical exercises, YAML files, commands, and notes:

| Folder | Description |
|--------|-------------|
| `00-linux-basics` | Linux fundamentals for Kubernetes (commands, permissions, processes, networking) |
| `01-container-fundamentals` | Containers theory and practice |
| `02-docker-basics` | Docker installation, images, containers, volumes, networks |
| `03-kubernetes-architecture` | Kubernetes components, architecture, control plane vs nodes |
| `04-cluster-setup` | Minikube / Kind cluster setup, first pods |
| `05-pods` | Creating and managing pods |
| `06-replicasets` | ReplicaSets, scaling, self-healing |
| `07-deployments` | Deployment YAML, updates, rollbacks |
| `08-services` | Service types, ClusterIP, NodePort, LoadBalancer |
| `09-configmaps` | Configuration management using ConfigMaps |
| `10-secrets` | Managing sensitive data securely |
| `11-volumes` | Persistent storage in pods |
| `12-persistent-storage` | PersistentVolume (PV) & PersistentVolumeClaim (PVC) |
| `13-ingress` | Ingress resources and routing |
| `14-rbac` | Role-based access control, service accounts |
| `15-network-policies` | Pod network security policies |
| `16-helm` | Helm charts and package management |
| `17-hpa` | Horizontal Pod Autoscaling |
| `18-monitoring` | Cluster monitoring, metrics, and logging |
| `19-troubleshooting` | Debugging pods, events, and cluster issues |
| `20-cka-practice` | CKA exam-style scenarios and practice labs |

---

## ⚡ Key Highlights

- Step-by-step **practical exercises**  
- YAML files for pods, deployments, services, and more  
- Linux and Docker foundations for Kubernetes  
- Minikube / local cluster setup  
- CKA-focused exercises for exam preparation  

---

## 🛠️ Tools Used

- **Linux (Ubuntu 24.04 WSL2)** – base OS for learning  
- **Docker Desktop** – container runtime and Docker CLI  
- **kubectl** – Kubernetes CLI  
- **Minikube / Kind** – local Kubernetes cluster  
- **Git & GitHub** – version control and documentation  
- Optional: **Helm** – package manager for Kubernetes  

---

## 📖 How to Use

1. Clone this repository:

```bash
git clone https://github.com/YOUR-USERNAME/Kubernetes-from-Scratch.git
cd Kubernetes-from-Scratch

2. Navigate to the topic folder you want to practice:

cd 00-linux-basics


3. Follow the exercises and add your own outputs/screenshots.

4. Commit your work back to GitHub:

git add .
git commit -m "Completed Day X exercises"
git push origin main

🎯 Outcome

By the end of this journey, you will be able to:

Confidently run Kubernetes clusters locally

Deploy, scale, and manage applications using Pods, Deployments, and Services

Manage secrets, volumes, and configurations

Implement RBAC and network policies

Troubleshoot and debug Kubernetes clusters like a professional

Be fully prepared for the CKA exam

🔗 References

Kubernetes Official Documentation

Docker Documentation

CKA Exam Curriculum