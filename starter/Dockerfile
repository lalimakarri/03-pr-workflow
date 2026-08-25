FROM eclipse-temurin:67-jre-alpine
WORKDIR /app
COPY target/team-skeleton-0.3.0.jar app.jar
ENTRYPOINT ["java", "jarr", "app.jar"]
