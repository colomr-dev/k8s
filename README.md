# Kubernetes Learning Path 🚀

This repository is dedicated to learning Kubernetes, starting with local development using Minikube and progressing to production-grade deployments with Google Kubernetes Engine (GKE).

## Learning Path Overview 📚

### Level 1: Basics (Minikube) 🌱
- [ ] Install Minikube and kubectl
- [ ] Create first pod
- [ ] Deploy simple application
- [ ] Understand basic kubectl commands
- [ ] Work with namespaces

### Level 2: Core Concepts 🔧
- [ ] Deployments and ReplicaSets
- [ ] Services (ClusterIP, NodePort, LoadBalancer)
- [ ] ConfigMaps and Secrets
- [ ] Persistent Volumes
- [ ] StatefulSets

### Level 3: Advanced Topics 🎯
- [ ] Ingress Controllers
- [ ] Custom Resource Definitions
- [ ] RBAC and Security
- [ ] Helm Charts
- [ ] Monitoring with Prometheus

### Level 4: Production (GKE) ☁️
- [ ] GKE cluster setup
- [ ] Cloud Load Balancing
- [ ] Cloud IAM integration
- [ ] Autoscaling
- [ ] Production best practices

## Local Setup Instructions 💻

1. Install Minikube:
```bash
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube
```

2. Start cluster:
```bash
minikube start
```

3. Verify installation:
```bash
kubectl get nodes
```

## Progress Tracking ✅
- Create an issue for each topic you're working on
- Use PR's to document learnings
- Tag completed items in this README

## Resources 📖
- [Kubernetes Documentation](https://kubernetes.io/docs/home/)
- [GKE Documentation](https://cloud.google.com/kubernetes-engine/docs)
- [Kubernetes Patterns](https://kubernetes.io/docs/concepts/cluster-administration/manage-deployment/)
