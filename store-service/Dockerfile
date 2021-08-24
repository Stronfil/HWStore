FROM openjdk:11
WORKDIR /app
COPY target .
EXPOSE 8190
ENTRYPOINT ["java", "-jar", "store-service-0.0.1-SNAPSHOT.jar"]