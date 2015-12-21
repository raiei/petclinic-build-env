FROM jenkins 
COPY plugins.txt /plugins.txt 
RUN /usr/local/bin/plugins.sh /plugins.txt 
USER root
RUN apt-get update; apt-get install -y maven
USER jenkins
