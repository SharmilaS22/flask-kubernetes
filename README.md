### build image
```docker build -t flask-app .```

### Minikube start
```minikube start```

### set env
```minikube docker-env```
```eval $(minikube -p minikube docker-env)```

### apply
```kubectl apply -f hello-deployment.yaml```
```kubectl apply -f hello-service.yaml```

### dashboard view
```minikube dashboard```

### get url
```minikube service hello-service --url```


