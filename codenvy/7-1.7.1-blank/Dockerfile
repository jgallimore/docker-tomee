#Reuse codenvy/jdk7 existing image
FROM codenvy/jdk7

# Expose ports
EXPOSE 8080

ENV CODENVY_APP_PORT_8080_HTTP 8080
 
# Download TomEE
RUN mkdir -p /home/user/tomee && \
    cd /home/user/tomee && \
    wget "http://apache.rediris.es/tomee/tomee-1.7.1/apache-tomee-1.7.1-plus.tar.gz"
	
CMD ["/bin/bash"]