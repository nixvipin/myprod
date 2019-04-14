FROM tomcat
ARG war_ver
ARG NEXUS_IP
ENV war_ver1=${war_ver}
ENV NEXUS_IP1=${NEXUS_IP}
ADD http://$NEXUS_IP1:8081/repository/maven-releases/com/employees/springmvc/employees/$war_ver1/employees-$war_ver1.war /usr/local/tomcat/webapps/myapp.war
EXPOSE 8080

