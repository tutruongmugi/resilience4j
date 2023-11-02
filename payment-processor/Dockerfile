FROM openjdk:17-jdk-slim
WORKDIR /opt
ENV PORT 1010
EXPOSE 1012
COPY target/*.jar /opt/app.jar
ENTRYPOINT exec java $JAVA_OPTS -jar app.jar