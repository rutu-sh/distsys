# Introduction

In the last scenario, we performed a lot of steps to get our application running. 
Here's a list of all the steps we did: 

1. Download the source code 
2. Install virtual environment support for Python
3. Create virtual environment
4. Activate virtual environment
5. Install the required packages
6. Run the game server

We realized that Doing all this manually for every server that should run your application could be **too much**. 

It would be better if we could automate this into a **Blueprint** that could be run anywhere with a **single command**.

[Docker](https://www.docker.com/) lets us do exactly that! 

This scenario takes you through basics of Docker and **Dockerizing** the application. 