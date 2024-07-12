# docker-implementations


#git add -A ; git commit -m 'updated project' ; git push

git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

docker ps -q

docker build -t IMAGE_NAME:IMAGE_TAG .

docker build -t apache-web:V1 .

docker build -t apache-web:v2 .

docker run --name nginx-webserver -p 80:80 -d apache-web:v2

docker run --name nginx-webserver -p 80:80 -d nginx:latest

docker build -t apache-web .

docker run -it --entrypoint /bin/bash apache-web df -h
