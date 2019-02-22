FROM tomcat:8.5
LABEL maintainer="Sergey Vasilenko <sergey@vasilenko.io>"
COPY midtier_linux.war /usr/local/tomcat/webapps/arsys.war
COPY arsys.xml /usr/local/tomcat/conf/Catalina/localhost/arsys.xml
CMD ["catalina.sh","run"]