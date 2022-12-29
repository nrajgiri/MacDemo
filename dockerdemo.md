# DevOps Foundations: My First Project

# Docker installation
why we need VM
  if you are window 10  HOME the we need Oracle VM VirtualBox
    other wise we don't need VM
    
 for mac we don't need VM
 
 
 # Docker for Mac
 --------------------
 
 
 docker for Mac gives us two things.
      1. small Linux virtual macnine hosting and running docker containers
      2. command line client for interacting with those containers
      3. Docker for Mac also installs docker compose -- tools for linking multiple contianers together
      
# using Homebrew to installing application on my Mac
open terminal
      - install brew
      - brew cask install docker
      - after installed, seach docker in your computer and logo will appear - create a docker account
      - docker run hello-world
      - Dockerfile
      - vim Dockerfile (we can open Dockerfile in any editor file like sublime, VSCODE)
      
      -----------------------------------------------------------------
      
      brew install docker  - docker command line interface
      brew cask install docker - install docker , docker compose, docker client
      
      There's different between brew install and brew cask install 
       brew cask install - instlls packages from third party repositories
            docker compose and the docker command line clinet
       How to create image?
       $ docker 
            
            
   -------
   - create 2 files
   - .dockerignore File - tells you what you don't include in the container
        node_modles npm-debug.log 
   - Docker File - purpose of a Docker file is to create an image based on the instructions on Docker File.
      instructins - From node  WORKDIR 
   
  - docker-compose and it's a YAML file
      instructions to create (that we need)
      
      
 Docker - Basic Commands
 - docker pull
 - docker run
 - docker start
 - docker stop

Difference Image and Container
Container is a running enviroment for Image



            
     # Traditional Configuration Management Tools
     ============================================
     1. Chef
     2. Puppet
     3. Ansible 
     4 CFEngine
     
     
     
     
     
     
     
            
 
 
