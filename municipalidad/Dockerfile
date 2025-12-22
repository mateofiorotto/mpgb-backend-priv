FROM eclipse-temurin:21
ARG JAR_FILE=target/municipalidad-0.0.1.jar
COPY ${JAR_FILE} app_municipalidad.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_municipalidad.jar"]