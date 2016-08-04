FROM jenkins:2.7.1-alpine
USER root

# install plugins
COPY plugins.txt /plugins.txt
RUN /usr/local/bin/plugins.sh /plugins.txt
