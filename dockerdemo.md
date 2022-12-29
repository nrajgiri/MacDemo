# Devops
  linux
  

# Basics of AWS Cloud
server
configuration - each and every minute details of your Machine (server, storage)
Automation Tool - CHEF




# CHEF - configuration Management Tool
    system asministrator
    


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
      
      -------------------------------------------------------------------------
      
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
     
     
     
     
     
     What is Docker and how it works?
          -prerequiste - vm ware
          
     Container is like a Virtual Machine
     Docker or Docker Engine is a tool which create this VM
    
     to run application we need dependencies 
     to run some applicatinon we need some dependencies in our system. 
     or we need compatable version for that version
     
     
     
     Development + Operation(Deploy to Server)
      - Dependencies
     
     - Infratructure - Hardware - window - Hypervisor - 
     
    Revise =>  Hypervisor -  help create Vritual Machine (Virtualization)
    
    
    # Docker
    docker is a advance version of Virtualization
    docker   help in  Containerization
     
      Virtualization == Containerizatin
     Hypervisor == Docker Engine 
     vm = ec2 intance = Docker Engine
     
     What is Hypervisor?
     - create and run Virtual Macnine and called Virtual Machine Manager(VMM)
     
     
     what is software, formware, hardware?
     
     
     Type of Hypervisor
      - type1(Bare Metal or Netive Hyper) and type2(Hosted Hpervisor)
      
   What is Virtualization
   
   h/w - os - docker engine - container - 
   
   docker -  is a deployement tool.
   
   docker create container and CHEF do configuration
   container is VM. provider all  dependencies for our application.
   container is running state of image.
   
   
   # Docker Hub
   
   # Virtualisation
    Platform as a Service
 Iaas
 Saas
 Paas
   
   
     docker 
   # Docker Architecture 
 

 
 
