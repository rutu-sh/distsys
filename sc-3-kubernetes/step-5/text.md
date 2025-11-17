# Kubernetes Basics


### Creating the game server deployment

Open the `game_deployment.yaml` file in the editor. 

Paste the following content in the file: 


```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: game-server
spec:
  replicas: 3
  selector:
    matchLabels:
      app: game-server
  template:
    metadata:
      labels:
        app: game-server
    spec:
      containers:
        - name: game-server-container
          image: rutush10/python-game-server-redis:v0.0.3
          ports:
            - containerPort: 8080
          env:
            - name: REDIS_HOST
              value: "redis"        # matches redis Service name
            - name: REDIS_PORT
              value: "6379"
          resources:
            requests:
              cpu: "250m"
              memory: 256Mi
            limits:
              cpu: "250m"
              memory: 256Mi
```

This defines a deployment that looks like this

![](./assets/deployment-example.png)





