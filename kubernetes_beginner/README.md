You can click on the below links to check for the images used in the YAML file.
1. [Worker](https://hub.docker.com/r/kodekloud/examplevotingapp_worker/tags)
2. [Vote](https://hub.docker.com/r/kodekloud/examplevotingapp_vote/tags)
3. [Result](https://hub.docker.com/r/kodekloud/examplevotingapp_result/tags)


## Commands to run pods.yaml and service.yaml.

```
kubectl create -f voting-app-pod.yaml

```
```
kubectl create -f voting-app-service.yaml
```
```
kubectl create -f result-app-pod.yaml
```
```
kubectl create -f result-app-service.yaml
```
```
kubectl create -f redis-pod.yaml
```
```
kubectl create -f redis-service.yaml
```
```
kubectl create -f postgress-pod.yaml
```
```
kubectl create -f postgress-service.yaml
```
```
kubectl create -f worker-pod.yaml
```

Commands to check the pods and service
```
kubectl get pods,svc
```
![image](https://github.com/sayanalokesh/voting_app_k8s/assets/105637305/ae32d38e-4719-4b10-bf40-da9c2adc7de7)

![image](https://github.com/sayanalokesh/voting_app_k8s/assets/105637305/40faa28b-8f63-4148-9cf9-ec94690a9a29)
![image](https://github.com/sayanalokesh/voting_app_k8s/assets/105637305/36b30971-8594-41d2-99de-0a445a317be4)

## Commands to run deployment.yaml and service.yaml.
```
kubectl create -f voting-app-deployment.yaml

```
```
kubectl create -f voting-app-service.yaml
```
```
kubectl create -f result-app-deployment.yaml
```
```
kubectl create -f result-app-service.yaml
```
```
kubectl create -f redis-deployment.yaml
```
```
kubectl create -f redis-service.yaml
```
```
kubectl create -f postgress-deployment.yaml
```
```
kubectl create -f postgress-service.yaml
```
```
kubectl create -f worker-deployment.yaml
```
commands to get the link to access
```
minikube service result-service --url
minikube service voting-service --url
```
![image](https://github.com/sayanalokesh/voting_app_k8s/assets/105637305/460cfe35-4c5e-4995-a0cf-b6c1bb0c0cd6)
![image](https://github.com/sayanalokesh/voting_app_k8s/assets/105637305/f21d8de6-405b-4e2a-9b70-263505ae5d15)

Commands to check the deploymemnts and service
```
kubectl get svc,deployments
```
![image](https://github.com/sayanalokesh/voting_app_k8s/assets/105637305/0052c911-8658-42f4-bf53-dca8f3e8f828)
![image](https://github.com/sayanalokesh/voting_app_k8s/assets/105637305/83ace743-0936-42d4-b42a-27220a33e216)
![image](https://github.com/sayanalokesh/voting_app_k8s/assets/105637305/a2ff46fb-a297-42d0-80ec-5213f810c0e4)
