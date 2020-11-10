FROM openjdk:11-jre
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} admin-service.jar
ENTRYPOINT ["java","-jar", "-Dspring.profiles.active=dev","/admin-service.jar"]
