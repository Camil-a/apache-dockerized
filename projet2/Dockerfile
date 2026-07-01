FROM ubuntu:latest
RUN apt-get update && apt-get install -y apache2
RUN apt-get install -y nginx
EXPOSE 8080
CMD ["nginx", "-g", "daemon off;"]

    