FROM jenkins/jenkins:lts
 
ENV DEBIAN_FRONTEND noninteractive
 
USER root
RUN apt-get update
RUN apt-get install -y apt-cacher-ng
 
RUN apt-get install -y maven
 
EXPOSE 8080
 
EXPOSE 50000