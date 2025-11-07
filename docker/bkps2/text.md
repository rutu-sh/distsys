# Step-2: Running the server

**1. Run the game server**

Now that everything is in place, let's run the game server.

```
gunicorn --bind 0.0.0.0:8080 main:app
```{{copy}}


**2. Access the application**

To access the application [click here]({{TRAFFIC_HOST1_8080}})


**3. Close the game server**

Click the following to close the game server: 

```
# close the game server
```{{exec interrupt}}