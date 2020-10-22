# CogInt
Starting with "Example: Deploying PHP Guestbook application with Redis" for my own review

## How Tos
To Start minikube kubernetes cluster(w/ 1 node):
```
minikube start
```
To Stop minikube kubernetes cluster:
```
minikube stop
```

To apply Radis Master Deployment:
```
kubectl apply -f https://k8s.io/examples/application/guestbook/redis-master-deployment.yaml
```
To apply Radis Master Service:
```
kubectl apply -f https://k8s.io/examples/application/guestbook/redis-master-service.yaml
```

To apply Radis Slave Deployment:
```
kubectl apply -f https://k8s.io/examples/application/guestbook/redis-slave-deployment.yaml
```
To apply Radis Slave Service:
```
kubectl apply -f https://k8s.io/examples/application/guestbook/redis-slave-service.yaml
```

To apply Frontend Deployment:
```
kubectl apply -f https://k8s.io/examples/application/guestbook/frontend-deployment.yaml
```
To apply Frontend Service(NodePort):
```
kubectl apply -f https://k8s.io/examples/application/guestbook/frontend-service.yaml
```