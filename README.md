# Docker-Image
 
Docker is a containerization platform that allows developers to build, deploy, and run applications in containers. These containers are lightweight and isolated environments that include everything an application needs to run, such as code, libraries, and dependencies.

In this lab, we are gonne use a VM to create an image into an container to run a small code index.html using IPV4:port/folder

**Install docker**

    sudo apt install docker.io

**download a Docker image using ubuntu/nginx**

     sudo docker pull ubuntu/nginx

**Create and run an Nginx container based on Ubuntu with the container name 'web-server' on port 9090.**

     sudo docker run --name web-server -p 9090:80 -d ubuntu/nginx

**Create and run an Nginx container based on Ubuntu with the container name 'web-server' on port 9090.**

     sudo docker run --name web-server -p 9090:80 -d ubuntu/nginx

**Open an interactive terminal inside the container named 'web-server'.**

     sudo docker exec -it web-server /bin/bash

**Start a Docker container**

     sudo docker start web-server

**Open an interactive terminal inside the container named 'web-server'.**

     1- cd var/www/html/
     2- nano index.html

**Write a code into an index.html**

     1- Write your code here
     2- ctrl + x to To save (y)

**Demonstration**

![image](https://github.com/user-attachments/assets/6734af49-fea6-468e-a0d4-58c274792ac7)

