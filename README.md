# docker_project
This is my first project in docker as a beginner.
The goal of this project is to set up an environment that allows us to work on our WordPress plugins and themes.

Once we have our configuration, we can fire up our docker cluster with the docker-compose command: 

docker-compose up -d. 

This command will pull all our images and fire up our containers. So that when you hit

http://localhost:8081/wp-admin

you will find that you are directed to WordPress’ setup page where you will be asked to set up your new WordPress instance. 

You can also visit the phpmyadmin site by opening up http://localhost:8082 on your browser. 

Use the credentials below to access the phpmyadmin server:

username — root

password — example
