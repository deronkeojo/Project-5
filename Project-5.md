### CLIENT-SERVER ARCHITECTURE WITH MYSQL

### Understanding Client-Server Architecture
As you proceed your journey into the world of IT, you will begin to realise that certain concepts apply to many other areas. One of such concepts is – Client-Server architecture.

Client-Server refers to an architecture in which two or more computers are connected together over a network to send and receive requests between one another.

In their communication, each machine has its own role: the machine sending requests is usually referred as "Client" and the machine responding (serving) is called "Server".

### TASK – Implement a Client Server Architecture using MySQL Database Management System (DBMS).

### Create and configure two Linux-based virtual servers (EC2 instances in AWS).

### On mysql server Linux Server install MySQL Server software.

### On mysql client Linux Server install MySQL Client software.

### By default, both of your EC2 virtual servers are located in the same local virtual network, so they can communicate to each other using local IP addresses. Use mysql server's local IP address to connect from mysql client. MySQL server uses TCP port 3306 by default, so you will have to open it by creating a new entry in ‘Inbound rules’ in ‘mysql server’ Security Groups. For extra security, do not allow all IP addresses to reach your ‘mysql server’ – allow access only to the specific local IP address of your ‘mysql client’.

### You might need to configure MySQL server to allow connections from remote hosts.

`sudo vi /etc/mysql/mysql.conf.d/mysqld.cnf`

![database server-sudo apt update](./Database%20server-%20sudo%20apt%20update.png)

![database server-sudo systemctl enable mysql](./Database%20server0%20sudo%20systemctl%20enable%20mysql.png)

![Connection to Ubuntu database server](./Connection%20to%20Ubuntu%20database%20server.png)

![Connection to Client server succesfully](./Connection%20to%20client%20server%20succesfully.png)
