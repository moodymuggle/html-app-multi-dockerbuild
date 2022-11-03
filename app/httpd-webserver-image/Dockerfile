#syntax=docker/dockerfile:1.4
#Dockerfile 1.4 syntax declaration

#pull the httpd server image from public docker hub
FROM httpd:2.4

#Copy the preferred html page as index.html and assign different build contexts
COPY --from=html-app .  /usr/local/apache2/htdocs/index.html

#COPY --from=html-blue ../blue/src/hello-blue.html /usr/local/apache2/htdocs/index.html 
#COPY --from=html-green ../blue/src/hello-green.html /usr/local/apache2/htdocs/index.html 
#COPY --from=html-yellow ../blue/src/hello-yellow.html /usr/local/apache2/htdocs/index.html 

