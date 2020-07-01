

# Steps to setup on your own machine:
## Pre-requisites:
  - Virtual Box
  - Vagrant
  - Git Bash

# Step 1: Setup local folder
  - Create folder where you'd like to setup this project on your local machine
  - right click within the folder and select "Git Bash here". This will open the bash terminal within this folder.
  - Go to this repos main page and click the "Clone" button and copy the url it gives.
  - Go to your local machine's git folder where you want to clone this.
  - Right click within the folder and select ```git BASH here```
  - Type in ``` git clone repo [paste url of repo that you copied earlier here]``` and press enter



# Step 2: Create virtual machine
  - run bash and do ```vagrant up```
  - When the virtual machine is up and running do ```vagrant ssh``` to go into the vm
  - Once within the VM change directory to the app using ```cd /../home/ubuntu/app ```
  - Then type in ```npm start``` to start the app

  - From here on you should be able to access the app on http://192.168.10.100:3000/
