# Part-2: Running the server

### 1. Run the game server

Now that everything is in place, let's run the game server.

```
gunicorn --bind 0.0.0.0:8080 main:app
```{{copy}}

