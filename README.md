# mysql
# Docker Installation 
The steps for installing Docker can be found here:
  https://github.com/syntaxboard/postgres-docker
# Git Installtion 
The steps for installing Git can be found here:
  https://github.com/syntaxboard/postgres-docker
# Building the Docker
1. Create a directory on the local system and call it mysql.
2. Clone the mysql repository to that folder.
3. Open commmad prompt and run the Docker command from mysql as required.
## Command to run the docker 
   ```
   docker-compose up 
   ```
## Command to run the docker in the background
   ```
   docker-compose up --d
   ```
## Command to remove the container 
   ```
   docker-compose up down
   ```
## Command to force the docker recreate the image and container
   ```
   docker-compose up --force-recreate "Service Name Specified in the docker in this case it db"
   ```
## Command to list all the containers
   ```
   docker ps  -a
   ```
## Command to force remove the container
   ```
   docker ps  -a
   docker rm --force "conatiner_id" from the above command.
   ```
