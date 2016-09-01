# WordPress Project Template

## Setup



1. Make sure you have `docker` version *1.12.1* or higher and `docker-compose` *1.8.0* or higher installed.

        $ docker --version
        $ docker-compose --version
        
2. Build the wordpress and mariadb containers:
3. 
        $ docker-compose build


3. Run the server:

    $ docker-compose up

  The server is now available at localhost:8080

4. Give yourself ownership of the wp-content directory.

    $ sudo chown -R $USER:www-data wp-content

  The wp-content directory is now editable within blog.
  



## Installation

### Install docker

 * [Linux](https://docs.docker.com/engine/installation/mac/)
 * [Mac](https://docs.docker.com/engine/installation/linux/)
 * [Windows](https://docs.docker.com/engine/installation/windows/)

### Install docker-compose

[Install docker-compose](https://docs.docker.com/compose/install/)



