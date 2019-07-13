FROM tomcat
USER root
ARG war_ver
ARG NEXUS_IP
ADD http://${NEXUS_IP}:8081/repository/maven-releases/com/employees/springmvc/employees/${war_ver}/employees-${war_ver}.war /usr/local/tomcat/webapps/myapp.war
EXPOSE 8080
