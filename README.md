## AUTHOR : INDU THAKUR
# CREATE VIRTUAL MACHINE IN CLOUD
  To deploment of websites in the cloud platfrom you should create virtual mechine on the whatever cloud platform you are using (AWS, azure).

  After that install git on your virtual machine if already not install.
  And then clone your project repository from you github to your virtual machine.
  by using these commands:
           sudo apt install git
           sudo apt update
           sudo clone url_your_porject_repo
# Install dependency 
 Now switch to your project file location by using cd command follow with file loctaion.
 and here install dependency (install node and npm)
   
     sudo apt update
    
     curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh

     curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
  
This will install the nvm script to your user account. To use it, you must first source your .bashrc file:
      source ~/.bashrc
Now, you can ask NVM which versions of Node are available:
      nvm list-remote
You can install a version of Node by writing:
      nvm install v18.10.0
You can switch between installed versions with nvm use:
      nvm use v18.10.0
If you want to remove node.js
     sudo apt remove nodejs
NPM install:-
     sudo apt install npm
     npm install

# NGINX SERVER
## Prerequisites
You should have a regular, non-root user with sudo privileges.
sudo apt update
sudo apt install nginx

## Adjusting the Firewall
   sudo ufw app list
   sudo ufw allow 'Nginx HTTP'
   sudo ufw status
