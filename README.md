# Tor proxy

Prefered to run on linux platform.

url-to-tor-github: https://github.com/rdsubhas/docker-tor-privoxy-alpine.git

How to run tor proxy?

On your working directory clone the repository from the url.

Now run the container type in terminal of cloned directory: 

# sudo docker run -d -p 8118:8118 -p 9050:9050 rdsubhas/tor-privoxy-alpine

# Web-Crawler
Simple web crawler.

Prefered to run on linux platform.

url-to-crawler-github: https://github.com/kartuna/Web-Crawler.git

How to run the crawler service?

Go to your working directory and clone the repository from the url.

Now for creating the container type:

# sudo docker build -t crawler-service .

Now run the container on background:

# sudo docker run -d crawler-service

See logs of container you can type:

# sudo docker logs "container-name"

Close the container type: 

# sudo docker stop "container-name"

To export the database type:

# sudo docker export "container-id" > "container-id"-backup.tar
