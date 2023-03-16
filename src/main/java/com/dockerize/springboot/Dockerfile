FROM eclipse-temurin:17

LABEL mentainer = "websam@gmail.com"

WORKDIR /app

COPY target/springboot-docker-0.0.1-SNAPSHOT.jar /app/springboot-docker.jar

ENTRYPOINT ["java","-jar","springboot-docker.jar"]


