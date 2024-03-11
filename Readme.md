# Commands

## Guides to installed Minikube and started a local Kubernetes cluster

### Install Minikube

```bash
brew install minikube
```

### Start Minikube

```bash
minikube start
```

### Check Cluster Information

```bash
kubectl cluster-info
```

### Access Kubernetes Dashboard

```bash
minikube dashboard
```

## Create a Pod

### Apply the Pod definition to your cluster

```bash
kubectl apply -f my-pod.yaml
```

### Check the status of the Pod

```bash
kubectl get pods
```

## Create a Service

### Apply the Service definition to your cluster

```bash
kubectl apply -f my-service.yaml
```

### Check the status of the Service

```bash
kubectl get services
```

## ConfigMaps

### Apply the ConfigMap definition

```bash
kubectl apply -f my-configmap.yaml
```

### View the ConfigMap

```bash
kubectl get configmaps
kubectl describe configmap my-configmap
```

## Secrets

### Apply the Secret definition

```bash
kubectl apply -f my-secret.yaml
```

### View the Secret

```bash
kubectl get secrets
kubectl describe secret my-secret
```
