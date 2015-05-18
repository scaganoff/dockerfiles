FROM tomcat:latest
MAINTAINER Saul Caganoff <saul@sixtree.com.au>

COPY tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml

COPY ./spring-security-saml-1.0.0.RC2/sample/target/spring-security-saml2-sample.war /usr/local/tomcat/webapps/

EXPOSE 8080
CMD ["catalina.sh", "run"]
