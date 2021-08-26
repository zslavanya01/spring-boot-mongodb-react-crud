FROM      openjdk:8-jdk-alpine
LABEL     maintainer="lavanya"
VOLUME    /tmp
ARG       JAR_FILE=target/*.jar
COPY      ${JAR_FILE} springboot.jar
EXPOSE    8080
ENTRYPOINT ["java","-jar","springboot.jar"]