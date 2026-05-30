FROM eclipse-temurin:21-jdk
WORKDIR /app
COPY target/*.jar app.jar
COPY . .
ENV ENV_VALUE="Running in Docker"
EXPOSE 4000
CMD ["java","-jar","app.jar","--server.port=4000"]
