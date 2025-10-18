# Step-2: Running the server

Now that everything is in place, let's run the game server.


```
gunicorn --bind 0.0.0.0:8080 main:app
```{{copy}}


Now follow the instructions below to access the application: 

![](./assets/open-port-1.png)


Enter `8080` as the input and click on `Access`

![](./assets/open-port-2.png)


Now you can access the game! 


Click the following to close the game server: 


```
# close the game server
```{{exec interrupt}}