FROM openjdk:8
ADD target/spring-boot-sample-web-static-2.2.0.BUILD-SNAPSHOT.war docker-spring-boot.jar
EXPOSE 9001
ENTRYPOINT ["java","-jar","docker-spring-boot.jar","--server.port=9001"]

