FROM eclipse-temurin:21-jre

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} gatewayservice.jar

ENTRYPOINT ["java", "-jar", "/gatewayservice.jar"]

EXPOSE 7073