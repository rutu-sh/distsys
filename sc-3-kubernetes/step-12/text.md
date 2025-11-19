# Kubernetes Basics


### Creating the game service

First ensure we're in the correct directory: 

```
cd ~/gw-distsys-python-game-server-k8s
```{{copy}}


To create the service, run the following command: 

```
kubectl apply -f game_service.yaml
```{{copy}}


To view the services run the following command: 

```
kubectl get service
```{{copy}}

