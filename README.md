# 🚀 Aprendizaje de Kubernetes (K8s)

Este repositorio está dedicado a mi viaje de aprendizaje de Kubernetes, enfocándome en comprender los conceptos fundamentales a través de la práctica con Minikube antes de trasladar estos conocimientos a Google Kubernetes Engine (GKE).

## 🎯 Objetivos de Aprendizaje

- Dominar los conceptos básicos de Kubernetes
- Ganar experiencia práctica con Minikube
- Comprender la arquitectura de K8s
- Prepararse para implementaciones en GKE

## 📚 Ruta de Aprendizaje

### Nivel 1: Fundamentos
- Instalación de Minikube
- Conceptos básicos de K8s
- Primeros comandos kubectl

### Nivel 2: Pods y Deployments
- Creación y gestión de pods
- Implementación de deployments
- ReplicaSets y escalado

### Nivel 3: Servicios y Networking
- Tipos de servicios
- Configuración de networking
- Reglas de ingress

### Nivel 4: Almacenamiento y Configuración
- Volumes
- ConfigMaps
- Secrets

### Nivel 5: Observabilidad
- Monitoring
- Logging
- Health checks

### Nivel 6: Avanzado
- Service mesh con Istio
- Sidecar patterns
- Autoscaling

## 💪 Retos Prácticos

1. Desplegar una aplicación web simple
2. Implementar un balanceador de carga
3. Configurar auto-escalado
4. Establecer reglas de ingress
5. Integrar Istio

## 🚦 Comenzando

1. Instalar Minikube
```bash
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube
```

2. Iniciar cluster
```bash
minikube start
```

3. Verificar instalación
```bash
kubectl get nodes
```

## 📖 Recursos y Referencias

- [Documentación oficial de Kubernetes](https://kubernetes.io/docs/home/)
- [Minikube Getting Started](https://minikube.sigs.k8s.io/docs/start/)
- [GKE Documentation](https://cloud.google.com/kubernetes-engine/docs)

## 📊 Seguimiento de Progreso

- [ ] Nivel 1 completado
- [ ] Nivel 2 completado
- [ ] Nivel 3 completado
- [ ] Nivel 4 completado
- [ ] Nivel 5 completado
- [ ] Nivel 6 completado
