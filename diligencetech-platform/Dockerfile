FROM amazoncorretto:21-al2-generic-jdk
ARG JAR_FILE=target/diligencetech-platform-0.0.1.jar
COPY ${JAR_FILE} app_diligencetech.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_diligencetech.jar"]
