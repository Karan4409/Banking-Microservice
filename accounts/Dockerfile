FROM eclipse-temurin:21-jdk

LABEL "org.opencontainers.image.authors"="Karan"

WORKDIR /app
COPY target/accounts-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]