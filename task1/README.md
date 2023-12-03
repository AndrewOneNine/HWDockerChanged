docker build -t mynginx .  

docker run --name mynginx1 -p 8080:80 -d  mynginx
