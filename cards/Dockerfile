FROM eclipse-temurin:21-jdk

LABEL "org.opencontainers.image.authors"="Karan"

WORKDIR /app
COPY target/cards-0.0.1-SNAPSHOT.jar cards.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "cards.jar"]