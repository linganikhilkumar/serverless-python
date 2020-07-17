# serverless-python

Setup VM for serverless and python projects(Ubuntu) 

## install python3.6 and pip3 

    sudo apt-get update 
    sudo apt-get install python3 python3-pip 
    sudo apt-get install python3-venv
  

## install AWS CLI and configure    
  pip3 install awscli 

### configure  
  aws configure `note`:Provide Access keys and secret keys 

## install git and configure 
   apt-get install git 

## install NodeJS and NPM 

  curl -sL https://deb.nodesource.com/setup_lts.x | sudo -E bash - 

  sudo apt-get install -y nodejs 

  sudo apt-get install  npm 

## install serverless 

  sudo npm install -g serverless 
  serverless --version 
# Virtual ENV  
## Creating Virtual  environments
    python3 -m venv myenv
## using Virtual ENV 
    source myenv/bin/activate
## deactivating ENV
    deactivate
   
    
    
    

