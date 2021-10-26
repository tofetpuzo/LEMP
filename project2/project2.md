# LEMP IMPLEMENTATION
LEMP is an open source web application stack  used for developing high performance web application. 

This is used all over the world and with the advert of cloud services. Companies can now scale up or down going to their need. The process of implementing LEMP is explained in view to understanding how LEMP works. 

INSTALLATION OF NGINX WEB SERVER
___

By employing the Nginx webserver, Clients or Site visitors can view dynamic pages and gain access to contents that will meet their respective needs.

In order to install Nginx server. First, had to login to the aws account, I used the ec2 instance of t2 nano family with Ubuntu 20.04LTS.

I successfully configured the ec2 instance to communicate with local machine through the git bash terminal. 

![ubuntu](/LEMP/project2/images/ubuntu.png)

To install Nginx server, I had to run these commands.

`:~ $: sudo apt update `

`:~ $: sudo apt install nginx`

After, the installation of Nginx server. I had to check the status of Nginx on my terminal.

To check status of Nginx, I used used this command.

`:~ $: sudo systemctl status nginx`

