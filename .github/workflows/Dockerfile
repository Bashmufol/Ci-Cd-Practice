FROM openjdk:21-jdk-slim

WORKDIR /app

COPY target/github-actions-practice.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]