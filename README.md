You can click on the below links to check for the images used in the YAML file.
1. [Worker](https://hub.docker.com/r/kodekloud/examplevotingapp_worker/tags)
2. [Vote](https://hub.docker.com/r/kodekloud/examplevotingapp_vote/tags)
3. [Result](https://hub.docker.com/r/kodekloud/examplevotingapp_result/tags)


Commands to run pods.yaml and service.yaml.

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
