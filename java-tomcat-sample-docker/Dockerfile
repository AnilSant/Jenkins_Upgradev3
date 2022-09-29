# FROM tomcat:8.0
# RUN cp -a **/*.war /usr/local/tomcat/webapps/
# EXPOSE 8080
# CMD ["catalina.sh", "run"]

FROM tomcat:9.0
ADD production/java-tomcat-sample/target/java-tomcat-maven-example.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]