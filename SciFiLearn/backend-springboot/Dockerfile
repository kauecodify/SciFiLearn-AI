//FROM eclipse-temurin:17-jdk-alpine
FROM openjdk:17-jdk-alpine
WORKDIR /app
COPY target/backend.jar backend.jar
// RUN ./mvnw clean package -DskipTests
EXPOSE 8080
ENTRYPOINT ["java","-jar","backend.jar"]
// CMD  ["java","-jar","target/backend-0.0.1-SNAPSHOT.jar"]
