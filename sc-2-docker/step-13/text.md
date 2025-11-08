# Docker Basics

### Let's build a Docker image for our Python server

At this point everything is setup for our container to run. 


Now, at the end, we just have to add a command which docker should run whenever we create a new container. 

Paste this line in your Dockerfile: 

```
CMD ["gunicorn", "--bind",  "0.0.0.0:8080", "main:app"]
```{{copy}}


This performs the following step: 

6. Run the game server ✅


Perfect! Now our Dockerfile is ready and we can build a Docker image. 