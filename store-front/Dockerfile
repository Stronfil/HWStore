FROM openjdk:11
WORKDIR /app
COPY target .
EXPOSE 8189
ENTRYPOINT ["java", "-jar", "store-front-0.0.1-SNAPSHOT.jar"]