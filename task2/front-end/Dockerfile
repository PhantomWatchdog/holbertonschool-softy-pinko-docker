# Use the latest Nginx as the base image
FROM nginx:latest

# Update APT package lists
RUN apt-get update

# Upgrade currently installed packages
RUN apt-get upgrade -y

# Set the front-end directory to /var/www/html/softy-pinko-front-end
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
