FROM openjdk:11-jre-slim
LABEL authors="codebuffdev"

VOLUME /tmp

EXPOSE 8080

COPY target/* app.jar

ENTRYPOINT ["java", "-jar", "/app.jar"]