FROM openjdk:17-jdk-alpine
VOLUME /tmp
ARG JAR_FILE
COPY ${JAR_FILE} app.jar
#RUN pwd
#RUN ls -l
ENTRYPOINT ["java", "-jar", "/app.jar"]