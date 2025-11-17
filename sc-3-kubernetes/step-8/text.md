# Kubernetes Basics


### Creating the game server deployment

First ensure we're in the correct directory: 

```
cd ~/gw-distsys-python-game-server-k8s
```{{copy}}


To create the deployment, run the following command: 

```
kubectl apply -f redis_deployment.yaml
```{{copy}}


To view the deployment run the following command: 

```
kubectl get deployments
```{{copy}}


Now this deployment will create one pods of redis. 
We can view these pods by running the following command: 


```
kubectl get pods
```{{copy}}