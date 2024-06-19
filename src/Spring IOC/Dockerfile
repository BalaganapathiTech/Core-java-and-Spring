FROM openjdk:17-jdk-alpine
VOLUME /tmp
COPY target/product-0.0.1-SNAPSHOT.jar.original app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
EXPOSE 8080