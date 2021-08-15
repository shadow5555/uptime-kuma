# uptime-kuma
This is a really cool uptime monitoring tool of your services

# Create a volume
docker volume create uptime-kuma

# Start the container
docker run -d --restart=always -p 3001:3001 -v uptime-kuma:/app/data --name uptime-kuma louislam/uptime-kuma

Browse to http://localhost:3001 after started.

Change Port and Volume

docker run -d --restart=always -p <YOUR_PORT>:3001 -v <YOUR_DIR OR VOLUME>:/app/data --name uptime-kuma louislam/uptime-kuma

more info can be found 
https://github.com/louislam/uptime-kuma
