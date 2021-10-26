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

Screenshot of Nginx status.

![nginx](/LEMP/project2/images/nginx.png)

To access the server locally on my machine using the DNS name, I used this code. The server can also be accessed using the ip address, by using the second command.

`:~ $: curl http://localhost:80`

`:~ $: curl http://127.0.0.1:80`

To check if Nginx is correctly running on my web browser, I used the ip address of the server to ping using the command:

`:~ $: ping <ip address>`

After which i used the ip address to check if it was responding on the web browser. 

Screenshot of Nginx working on the ip address.

![ubuntu](/LEMP/project2/images/nginxs.png)


## INSTALLATION OF MYSQL 
___ 

The installation of mySQL on the server allows data to be stored 



