FROM openjdk:8
ADD target/spring-boot-sample-web-ui-2.0.2.RELEASE.jar docker-spring-boot-2.jar
EXPOSE 9000
ENTRYPOINT ["java","-jar","docker-spring-boot-2.jar","--server.port=9000", "--server.servlet.context-path=/ui" ]
