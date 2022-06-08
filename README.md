# docker-wordpress
docker compose for quick wordpress setup on nginx mysql php

Prerequisites
1. Ubuntu 20.04
2. Docker Engine
3. Docker compose

Steps
1. Change username password hostname etc in docker compose file under db service and wordpress service
2. Run "docker-compose up" to pull docker images
3. Exit docker 
4. change servername to as necessary in nginx.conf file found in Nginx directory under Volumes directory
5. Change user, password, db name and db host in wp_config.php in wordpress_data.
6. Run docker again and open browser url.  
