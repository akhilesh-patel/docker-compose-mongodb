# docker-compose-mongodb
Run it- docker-compose up -d

How to check MongoDB container is running or not?
docker ps 
docker volume ls
docker inspect container_name 
docker log conatiner_name 

############################
How to connect to MongoDB server
Via mongo Shell
mongo admin -u root -p rootpassword
Note that mongo command should be installed on the computer. On Linux this should be install mongodb-org-shell only. Refer to this for more detail https://docs.mongodb.com/manual/installation/
