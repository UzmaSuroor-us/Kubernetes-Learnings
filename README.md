


Kubernetes Learning Guide

A practical, beginner-friendly guide to learning Kubernetes, from fundamental concepts to advanced cluster internals.

This repository contains Kubernetes commands, YAML manifests, explanations, and hands-on examples to help you understand how Kubernetes resources work and how to manage applications running in a cluster.

📚 Topics Covered

- Workloads: Pods, Deployments, ReplicaSets, StatefulSets, DaemonSets, Jobs, and CronJobs.
- Networking: Services, Ingress, Network Policies, CNI, and kube-proxy.
- Configuration and Security: Namespaces, ConfigMaps, Secrets, RBAC, ServiceAccounts, and kubeconfig.
- Storage: Persistent Volumes, Persistent Volume Claims, StorageClasses, and CSI.
- Scheduling: Taints and Tolerations, Affinity and Anti-Affinity.
- Autoscaling: Horizontal Pod Autoscaler (HPA) and Vertical Pod Autoscaler (VPA).
- Extending Kubernetes: Helm Charts, Custom Resource Definitions (CRDs), and Operators.
- Kubernetes Internals: Admission Controllers, etcd, Control Plane, Kubelet, and Container Runtime.

🎯 Learning Objectives

- Understand Kubernetes architecture and core concepts.
- Learn essential "kubectl" commands with practical examples.
- Write and manage Kubernetes YAML manifests.
- Deploy, expose, scale, and troubleshoot applications.
- Configure application settings, secrets, networking, and persistent storage.
- Understand workload scheduling, security, and autoscaling.
- Explore Kubernetes internals and cluster components.
- Build practical skills for DevOps and cloud engineering.

🛠️ Prerequisites

- Basic Linux commands and terminal knowledge.
- Basic understanding of containers and Docker.
- Familiarity with YAML.
- "kubectl" installed and access to a Kubernetes cluster.
- Helm installed for Helm-related exercises.

You can practice using Minikube, Kind, Docker Desktop Kubernetes, or another Kubernetes cluster.

🚀 Getting Started

Clone the repository:

git clone <your-repository-url>
cd Kubernetes-Learning-Guide

Verify your Kubernetes setup:

# Check the kubectl client version
kubectl version --client

# Check available cluster nodes
kubectl get nodes

# Verify access to the Kubernetes API
kubectl cluster-info

# Check the current Kubernetes context
kubectl config current-context

Follow the examples, execute the commands, inspect the resources, and experiment with the YAML manifests in your own development cluster.

💡 How to Use This Repository

Each topic focuses on practical learning through commands, configuration examples, and usage comments.

1. Understand the concept.
2. Review the commands and YAML manifests.
3. Apply the examples to a test cluster.
4. Inspect resource status and events.
5. Experiment with configuration changes.
6. Practice troubleshooting common issues.

⚠️ Important Notes

- Commands may require different permissions depending on your cluster configuration.
- Some features require additional components, plugins, or custom resource definitions.
- Review manifests before applying them to a cluster.
- Avoid committing passwords, tokens, certificates, or other sensitive credentials.
- Use a development cluster for experiments that create, modify, or delete resources.

📌 Goal

Build a strong foundation in Kubernetes through consistent, hands-on practice, progressing from basic workload management to advanced networking, storage, security, autoscaling, and cluster architecture.

---

Learning by doing. Building DevOps skills one Kubernetes concept at a time.