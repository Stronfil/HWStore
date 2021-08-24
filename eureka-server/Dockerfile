FROM openjdk:11
WORKDIR /app
COPY target .
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "eureka-server-0.0.1-SNAPSHOT.jar"]