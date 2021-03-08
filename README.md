# docker-mongodb

build image :
- docker build -t mongodb:latest .

run image 
- docker run --name mongodb --rm -d -p 27017:27017  mongo:3.6.22-xenial