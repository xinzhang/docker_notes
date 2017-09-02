docker-machine ls

docker pull <imagename>

docker run -p 5000:3000 -v "/c/Users/Public/site:/var/www" -w "/var/www" node npm start

docker ps -a

docker stop xxx

docker rm $(docker ps -a -q)

