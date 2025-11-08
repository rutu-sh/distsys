# Docker Basics

### Let's build a Docker image for our Python server

Next, paste this line in your Dockerfile: 

```
COPY src .
```{{copy}}

Also add the following line to make sure we change directory to where our code is located: 

```
WORKDIR /src
```{{copy}}

This takes care of the following: 

1. Download the source code ✅

At this point our docker image is a linux system with Python and also contains our source code.
