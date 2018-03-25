# docker build -t nginx:1 .

# docker run -d --rm --name custom-nginx-p 8090:90 -e IP_ADDRESS=10.10.10.10

Inside your container
# docker exec -it custom-nginx sh 

# cat /etc/nginx/conf.d/default.conf
