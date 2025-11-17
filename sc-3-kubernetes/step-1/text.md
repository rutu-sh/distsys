# Kubernetes Basics


### Use the `kubectl` command

Let's see how our cluster looks from the command line. 
Run the following code to see the nodes in our Kubernetes cluster: 

```
kubectl get nodes 
```{{copy}}


It produces the follwing output: 

```
NAME           STATUS   ROLES           AGE   VERSION
controlplane   Ready    control-plane   28d   v1.34.1
node01         Ready    <none>          28d   v1.34.1
```

`controlplane` and `node01` are both the nodes in our Kubernetes cluster. 
We are on the `controlplane` node.

