# Understanding the code 

### The game has the following content

```
├── requirements.txt
├── game
│   ├── dino.html   
│   └── user.html
├── main.py
└── scores.json
```

**1. requirements.txt**

The `requirements.txt` file contains all the Python packages our server needs to run. 

```
Flask==3.1.2
gunicorn==23.0.0
```

In our case, we only need two packages to run our server: 

    1. **Flask**: Lets you define a web server in Python
    2. **gunicorn**: It runs the webserver written in Flask


The `pip3 install -r requirements.txt` command we ran before, reads this file and installs all the required packages.


**2. game**

The `game` directory contains the following HTML files: 

    1. **trex.html**: Has the code to display and run the trex game inside the browser.
    2. **user.html**: Has the code to display a user's best 5 scores.

**3. main.py**

This file defines how 