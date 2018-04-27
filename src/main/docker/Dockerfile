FROM hub.c.163.com/public/jdk:1.7.0_03
ADD pythonServer.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
