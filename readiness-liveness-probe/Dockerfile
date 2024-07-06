FROM openjdk:17
LABEL authors="codebuffdev"

VOLUME /tmp

EXPOSE 8081

COPY target/readiness-liveness-probe-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-jar", "/app.jar"]