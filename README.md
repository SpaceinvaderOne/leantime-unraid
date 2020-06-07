
<img src="https://leantime.io/logos/leantime-logo-transparentBg-landscape-1500.png" width="400"/>

# Leantime Container #

Leantime is an open source project management system for small teams and startups written in PHP, Javascript using MySQL. [https://leantime.io](https://leantime.io)

This is a container for use with Unraid. For other systems please use the official image here <a href="https://hub.docker.com/r/leantime/leantime">Docker image for Leantime</a>. It was built using the <a href="https://github.com/Leantime/leantime/releases">latest Leantime release</a>.



## Setup Mariadb

Download and install mariadb from communtity applications.

Bash into the container

Login with password setup in the container template

mysql -uroot -p

create a user

CREATE USER 'leantime' IDENTIFIED by 'changeme!';

make a database

CREATE DATABASE IF NOT EXISTS leantime;

give permissions to database user/users

GRANT ALL PRIVILEGES ON meantime.* TO 'meantime' IDENTIFIED BY 'changeme!';

quit

## Setup Leantime Container

Install to Unraid from community Applications 

Fill in template 
