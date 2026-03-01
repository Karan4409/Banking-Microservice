FROM eclipse-temurin:21-jdk

LABEL "org.opencontainers.image.authors"="Karan"

WORKDIR /app
COPY target/loans-0.0.1-SNAPSHOT.jar loans.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "loans.jar"]