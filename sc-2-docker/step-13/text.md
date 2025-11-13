# Docker Basics

### Let's build a Docker image for our Python server

Next, paste this line in your Dockerfile: 

```
RUN pip3 install -r requirements.txt
```{{copy}}

This takes care of the following: 

6. Run the game server ✅

And ensures the following configurations: 

3. Python3 requirements (`flask==3.1.2` and `gunicorn==23.0.0`) ✅

Now we have everything needed to run the container available in the Image. 