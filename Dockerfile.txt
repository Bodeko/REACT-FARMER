#---------------------------------------------------------------------------
# Dockerfile to build Docker Image of NGINX WebServer with my Web Application
#
# Copyleft(c) by Denis Astahov
#---------------------------------------------------------------------------

FROM nginx:latest

COPY public/index.html /usr/share/nginx/html/index.html
