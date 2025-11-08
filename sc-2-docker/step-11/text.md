# Docker Basics

### Let's build a Docker image for our Python server

Next, paste this line in your Dockerfile: 

```
FROM python3.12.3-slim
```{{copy}}

This single step takes care of the following configurations:

1. A linux system ✅
2. Python3 version 3.12.3 ✅

Furthermore, this version does not require you to install and setup virtual environment for python.
Therefore, :

2. Install virtual environment support for Python ✅
3. Create virtual environment ✅
4. Activate virtual environment ✅


At this point, our Docker image is a linux system with Python installed. 
This docker image will look the same on any system it is present. 


We use **slim** image of Python because it contains only the required things and makes our docker image smaller in size. 

