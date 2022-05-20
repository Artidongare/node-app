# node-app
Created Dockerfile for node
- docker build -t .    -->. for taking from current folder
- after build image created
pull the code and created docker image
Created docker-compose.yml file 
- inside docker-compose file created mongo and sql ,pulled images from docker hub and created containers
- first its create mongo and mysql which are dependencies of node
using => docker-compose up -d
started the compose file
stop using => docker-compose down/stop
- stop: will simply stop
- down: will stopand remove
- start: start docker-compose which was stopped
