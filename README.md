# rdany-web
Website for rDany

docker build -t rdany-web .
docker create -l rdany-web --name=rdany-web -v /root/rdany-web:/usr/local/apache2/htdocs/ rdany-web:latest

