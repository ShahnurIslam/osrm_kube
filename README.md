Starting minikube
```
minikube start --cpus 4 --memory 8096 --disk-size=40g --driver=virtualbox
```
Starting the cluster
```
kubectl apply -f deployments.yaml -f service.yaml
```
To get the ip address for your code
```
minikube service osrm-lb  --url
```
