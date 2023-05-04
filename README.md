# Nginx reverse proxy server

Implemented an nginx reverse proxy server to serve static content hosted on vm's running docker containers. The project is built using a jenkins pipeline which takes the nginx configuration file and deploys it to the proxy server.




## Usage

This repo holds the dockerfiles to build an image, the index.html files containing the static content that will be served, and the nginx.conf files that will serve the static content on the docker containers. There is a separate branch for each index.html file as each container is unique in its content served to clearly display the load-balancing done by the reverse proxy server. 
