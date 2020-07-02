FROM adoptopenjdk/openjdk11:alpine-jre
VOLUME /tmp
ADD build/libs/springboot-web-0.0.1-SNAPSHOT.jar application.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "application.jar"]