# Full Stack Nano degree Project #7 

## Linux Server For the Cat-log Project Restaurants Menu 

## The Server Info 
- IP address ---> 35.192.210.27
- SSH Port ---> 2200
- Username ---> grader
- URL ---> http://35.192.210.27/

## Software Installed In The Project
- Apache2
- Postgresql
- Sqlalchemy
- Git
- Facebook
- Flask
- Libapache2-mod-wsgi
- Requests
- Httplib2
- Oauth2client

## Server Configuration 
- setup the server on Google Compute Engine 
- Download And Install Putty  and get the private key from it 
- Add new User name called grader using "$ adduser grader" command 
- add sudo privileges to the new user grader  using "$ sudo visusdo" command 
- add the following "grader ALL=(ALL:ALL) ALL" under "root ALL=(ALL:ALL) ALL "  
- back to the user grader 
- create .ssh file to grader 
- change ssh port to 2200

## Firewall Configuration 
- Enter Command "$ sudo ufw allow 2200/tcp"
- Enter Command "$ sudo ufw allow www"
- Enter Command "$ sudo ufw allow ntp"

## Sources
- [changing ssh port](http://ubuntuforums.org/showthread.php?t=1591681)
- [flask deployment](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
- [linux server configurations](https://discussions.udacity.com/c/nd004-p7-linux-based-server-configuration)
