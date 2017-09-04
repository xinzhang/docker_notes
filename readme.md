docker-machine ls

docker pull <imagename>

docker run -p 5000:3000 -v "/c/Users/Public/site:/var/www" -w "/var/www" node npm start

docker ps -a

docker stop xxx

docker rm $(docker ps -a -q)

docker build -t tag/node .

docker run -d -p 8080:3000 tag/node

#-----------------------------------

docker swarm init --advertise-addr ...:2377 --listen-addr ...:2377

docker swarm join-token manager
docker swarm join-token worker

docker node ls
docker node promote ...

# -----------------------------------------

docker exec nodeapp node dbSeeder.js

