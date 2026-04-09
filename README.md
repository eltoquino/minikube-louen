```
docker build -t loentq/my-service-java-rest:v2 .
```
```
docker login
```
```
docker push loentq/my-service-java-rest:v2
```
```
minikube kubectl -- apply -f myservice-deployment.yml
```
```
minikube kubectl -- apply -f myservice-service.yml
```
```
minikube service myservice-service --url
```
