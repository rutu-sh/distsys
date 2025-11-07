# Step-1: Setting up


**1. Download the source code**

Run the following command to clone the GitHub repository containing the source code for our game server. 

```
git clone https://github.com/rutu-sh/distsys-manifests.git
```{{copy}}

**2. Install virtual environment support for Python**

To run Python code, we need to install and setup virtual environment feature for Python. 
Run the following command to download the virtual environment setup for Python.


```
sudo apt install -y python3-venv
```{{copy}}


**3. Create virtual environment**

Next, run the following to change directory into the downloaded code. 


```
cd ~/distsys-manifests/docker/t-rex-game
```{{copy}}


Now run the following to create a virtual environment for our game server. 


```
python3 -m venv .venv
```{{copy}}


**4. Activate virtual environment**

Activate the virtual environment by running the following command 


```
source .venv/bin/activate
```{{copy}}


**5. Install the required packages**

Lastly, install the required packages needed for running the game server. 


```
pip3 install -r requirements.txt
```{{copy}}


Now the setup is complete for running our game server. 



