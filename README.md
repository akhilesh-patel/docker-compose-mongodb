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


![Screenshot (795)](https://user-images.githubusercontent.com/64592542/145167854-8ddaaecb-2850-4ed1-899f-ec6736357a64.png)

 docker commit  database_mongodb_container_1 akhil_mongodb:v1
 docker images convert to tar file
 docker save -o /root/akhil_mongodb.tar  akhil_mongodb
 

 extraxt file
 tar -xvf  akhil_mongodb.tar
 
 



