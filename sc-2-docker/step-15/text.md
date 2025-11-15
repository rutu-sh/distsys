# Docker Basics

### Let's build a Docker image for our Python server


The dockerfile should look like this. If you could not follow the previous steps, replace the contents of your Dockerfile with this:

```yaml
FROM python:3.12.3-slim
WORKDIR /src
COPY src .
RUN pip3 install -r requirements.txt
CMD ["gunicorn", "--bind",  "0.0.0.0:8080", "main:app"]
```{{copy}}

Open the terminal and change directory: 

```
cd ~/gw-distsys-docker-introduction
```{{copy}}


