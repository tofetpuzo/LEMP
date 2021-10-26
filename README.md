# LEMP
LEMP Implementation

This is my second project, it entails the implementation of LEMP. 
LEMP is an open source web application stack which facilitates the development of website applications. 
A stack usually consists of an operating system such as LINUX, WINDOWS and MAC IOS, a database such as myQSL, Oracle Database, server-side as well as the client-side web browser technologies, . 

LEMP is usually used around the world to deploy web applications. The term LEMP is an acronym. which stands for L: Linux operating system, Nginx (Engine -X Server), M: MySQL database and PHP: scripting language

Steps for implementing LEMP
1. Create a free account in AWS Cloud services.
2. Create an EC2 instance of t2.nano family with Ubuntu Server 20.04LTS in aws management console.
3. Instantiate the EC2 , download the key pair, navigate to download folder and use this code below to allow communication between your machine terminal and the aws server.
 :$ ssh -i "key-name" ubuntu@ip
