# Kubernetes Basics


### Creating the game server deployment

First ensure we're in the correct directory: 

```
cd ~/gw-distsys-python-game-server-k8s
```{{copy}}


To create the deployment, run the following command: 

```
kubectl apply -f game_deployment.yaml
```{{copy}}


To view the deployment run the following command: 

```
kubectl get deployments
```{{copy}}


Now this deployment will create three pods of game-server. 
We can view these pods by running the following command: 


```
kubectl get pods
```{{copy}}

Copy the name of one of the pods and run the following command with it: 

```
kubectl delete pod <pod-name>
```{{copy}}


We deleted one of the 3 pods, but the deployment should have scheduled a new one in its place.