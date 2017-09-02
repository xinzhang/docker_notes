docker-machine ls

docker pull <imagename>

docker run -p 5000:3000 -v "/c/Users/Public/site:/var/www" -w "/var/www" node npm start

docker ps -a

docker stop xxx

docker rm $(docker ps -a -q)

docker build -t tag/node .

docker run -d -p 8080:3000 tag/node