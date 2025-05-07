FROM openjdk:21-jdk
LABEL maintainer="cs01532@gmail.com"
ARG JAR_FILE=build/libs/gitlab-0.0.1-SNAPSHOT.jar
ADD ${JAR_FILE} docker-springboot.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/docker-springboot.jar"]
