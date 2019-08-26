# example di Dockerfile
Dalla folder eseguire i seguenti comandi

#build immage
docker build -t esempio-docker-file/node-web-app:0.0.1 .

#get image list
docker images -list

#run container
docker run -p 49160:8080 -d esempio-docker-file/node-web-app:0.0.1