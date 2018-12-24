FROM java:8-jre-alpine
RUN mkdir /myapp
WORKDIR /myapp
COPY target/spring-boot-sample-data-rest-2.2.0.BUILD-SNAPSHOT.jar .
EXPOSE 8080
ENTRYPOINT java -jar spring-boot-sample-data-rest-2.2.0.BUILD-SNAPSHOT.jar
