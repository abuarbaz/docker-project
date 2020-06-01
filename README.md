# docker-project
git remote add origin https://github.com/abuarbaz/docker-project.git


git push --set-upstream origin master


Create a Dockerfile with the content



docker build -t getting-started .



docker run -dp 3000:3000 getting-started

docker stop imagename

docker ps -a gives you the image name

docker run -d ubuntu bash -c "shuf -i 1-10000 -n 1 -o /data.txt && tail -f /dev/null"

docker exec <container-id> cat /data.txt
  
docker run -it ubuntu ls /
docker rm -f "To remove containers
docker network create todo-app

docker volume create todo-db
docker run -dp 3000:3000 -v todo-db:/etc/todos getting-started

docker volume inspect

docker logs -f <container-id>

sudo docker-compose up -d

sudo docker-compose down
