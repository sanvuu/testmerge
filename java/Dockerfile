FROM openjdk:11-jre-slim
WORKDIR /test/java
COPY ./java/*.jar ./application.jar
ENTRYPOINT ["java", "-jar", "./application.jar"]
