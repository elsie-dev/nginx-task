# TASK

Using ansible and vagrant to build up applications for webserver and loadbalancing,which brings up the ip address they belong to.\\
Loaded up 2 servers and a loadbalancer for them to be exposed.
However deployment of the application is still incomplete.

## Setting up Vagrant
Requirements
1. Vagrant software
2. Oracle virtual box
3. Have python installed 
4. Ansible installed correctly
5. GITfor version control

The application for running "hello world" is written in python

## How to run 

On a vigrant box  

``` vagrant up```


## **Compromises:**
Virtual box with name loadbalancer already exists.
 - removing load from the vagrant file then doing ```vagrant up``` solved the error.
   
