FROM openjdk:11-jre
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} client-service.jar
ENTRYPOINT ["java","-jar", "-Dspring.profiles.active=dev","/client-service.jar"]
EXPOSE 8080