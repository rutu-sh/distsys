# Docker Basics

### Understand the docker run command

We ran the following command to start our container. Let's understand more about that command: 


```
docker run -d --name hello-world -p 8080:80 docker/welcome-to-docker 
```


The command has the following parameters: 

1. `docker`: the docker command-line tool
2. `run`: is the subcommand telling docker that we want to run a container 
3. `-d`: is a parameter that tells docker to run this container quietly in the background
4. `--name hello-world`: tells docker to name this container `hello-world`
5. `-p 8080:80`: tells docker to send traffic from port `8080` on our machine to port `80` on the container. 
6. `docker/welcome-to-docker`: is the publicly available docker image we are using to run this container. 


