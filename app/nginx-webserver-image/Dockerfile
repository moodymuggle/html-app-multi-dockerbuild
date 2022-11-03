#syntax=docker/dockerfile:1.4
#Dockerfile 1.4 syntax declaration

#pull the nginx server image from public docker hub
FROM nginx:stable

#Copy the preferred html page as index.html and assign different build contexts
COPY --from=html-app . /usr/share/nginx/html/