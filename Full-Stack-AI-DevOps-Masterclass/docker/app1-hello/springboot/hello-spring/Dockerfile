FROM eclipse-temurin:21-jre
WORKDIR /app
COPY target/*.jar app.jar
COPY . .
ENV ENV_VALUE="Running in Docker"
EXPOSE 8080
CMD ["java","-jar","app.jar"] 
