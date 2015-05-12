FROM codenvy/jdk7_vnc

RUN sudo apt-get update

# Expose ports
EXPOSE 8080

# Download TomEE
RUN mkdir -p /home/user/tomee && \
    cd /home/user/tomee && \
    wget "http://apache.rediris.es/tomee/tomee-1.7.1/apache-tomee-1.7.1-plus.tar.gz"
