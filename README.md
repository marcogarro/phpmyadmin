# phpmyadmin
Simple phpmyadmin and mariadb installation using docker and docker-compose

First you need to install on your system **[Docker](https://www.docker.com/get-started)** and **[Docker-Compose](https://docs.docker.com/compose/install/)**

Get this project:

`$ git clone https://github.com/marcogarro/phpmyadmin.git`

`$ cd phpmyadmin`

Edit docker-compose.yaml

Choose your MariaDB root passwords and set the MYSQL_ROOT_PASSWORD environment variables.

Start the service:

`$ sudo docker-compose up -d` 

Goto your phpMyAdmin tool here: http://localhost:8081

The **credentials** are: 

Username: root

Password: your_root_password

To start the service run: 

`$ sudo docker-compose up -d`

To stop the service run:

`$ sudo docker-compose down`
