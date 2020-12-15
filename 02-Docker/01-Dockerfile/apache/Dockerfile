# Base Image
FROM ubuntu:16.04

# Owner of the Image
MAINTAINER Amit Vashist <amitvashist7@outlook.com>

# Update the Apt Repo. 
RUN apt-get update 

# Install Apache Packages 
RUN apt-get install apache2 -y 

# Custom Web Page
COPY info.html /var/www/html/info.html

# Bring up the Service 
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
