docker ps -a
docker-compose up
docker rm container_name


docker build --tag flask-docker .
docker run -d -p 5000:5000 flask-docker