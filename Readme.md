# Commands to start

## KUBEAPPS Documentation

<https://kubeapps.dev/docs/latest/tutorials/getting-started/>

## minikube Documentation

<https://minikube.sigs.k8s.io/docs/start/>

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

## ReplicaSets and Deployments

### Apply the ReplicaSet definition

```bash
kubectl apply -f my-replicaset.yaml
```

```bash
kubectl get replicasets
kubectl get pods
```

```bash
kubectl apply -f my-deployment.yaml
```

```bash
kubectl get deployments
kubectl get pods
```

## Ingress

### Apply the Ingress definition

```bash
kubectl apply -f my-ingress.yaml
```

### Check the status of the Ingress

```bash
kubectl get ingresses

```

### To test the Ingress, update your local /etc/hosts file to map my-ingress.local to the Minikube IP

```bash
sudo echo "$(minikube ip) my-ingress.local" >> /etc/hosts
```
