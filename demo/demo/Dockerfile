FROM adoptopenjdk:11-jre-hotspot

WORKDIR /app

EXPOSE 8080

ARG JAR_FILE=target/*.jar
ADD ${JAR_FILE} app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]