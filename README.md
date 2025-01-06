To run docker setup: 
docker ps -q | ForEach-Object { docker stop $_; docker rm $_ }
docker-compose up --build 
