FROM tomcat:9.0.99
EXPOSE 8081
COPY ./webapps /usr/local/tomcat/webapps
COPY ./server.xml /usr/local/tomcat/conf/server.xml
CMD ["catalina.sh", "run"]