# Mongo express and MongoDb with Kubernetes

Deploy a Mongo express server connected to a mongodb database

## Installation

```
kubectl apply -f .
```

## Access to the dashboard

Check minikube ip :
```
minikube ip
```

Find the port used by mongo express :
```
kubectl get svc
```

Go to the url <minikube_ip>:<mongo-express-port>

## Alternative

The load balancer may be replaced by a simple nodePort :
You can have a look on the use_nodeport branch

## Explanations


https://www.bogotobogo.com/DevOps/Docker/Docker_Kubernetes_MongoDB_MongoExpress.php