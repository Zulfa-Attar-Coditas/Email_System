FROM eclipse-temurin:8-jdk-alpine
VOLUME /tmp
COPY target/*.jar Email_System-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/Email_System-0.0.1-SNAPSHOT.jar"]
EXPOSE 8080