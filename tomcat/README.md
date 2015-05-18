
== Tomcat Container with Manager ==

Users config contains an admin user named "admin" with password "admin".

docker build -t tomcat:with-manager .

To run:

docker run -d --name tomcat -p 8080:8080 tomcat:with-manager

