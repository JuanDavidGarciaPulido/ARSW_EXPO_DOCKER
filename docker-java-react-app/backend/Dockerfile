# Usar la imagen estándar de OpenJDK 17
FROM openjdk:17-jdk
WORKDIR /app
COPY target/docker-java-react-app-1.0-SNAPSHOT.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]
