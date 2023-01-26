# Getting Started

Make sure minikube is running on local machine

Create service and deployment
```
kubectl create -f deployment.yaml
```

Open minikube dashboard
```
minikube dashboard
```

Connect Kubernetes cluster to local machine
```
minikube tunnel
```

Open browser at `localhost:8080`