FROM open:17-jdk-slim
ADD  /build/libs/*.jat app.jar
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar","/app.jar"]

