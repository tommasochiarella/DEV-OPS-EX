# example di Dockerfile
Dalla folder eseguire i seguenti comandi

#build immage
docker build -t esempio-docker-file/node-web-app:0.0.1 .

#get image list
docker image -list

#run container
docker run -p 8081:8080 -d esempio-docker-file/node-web-app:0.0.1



#effettuare le modifiche al file 
//scommentare

#build immage
docker build -t esempio-docker-file/node-web-app:0.0.2 .

#get image list
docker image -list

#run container
docker run -p 8082:8080 -d esempio-docker-file/node-web-app:0.0.2