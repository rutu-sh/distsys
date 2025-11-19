# Kubernetes Basics


### Creating the redis server deployment

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

