FROM openjdk:17-jdk-slim

WORKDIR /app

# Copiar el JAR construido
COPY target/*.jar app.jar

# Puerto de Eureka Server
EXPOSE 8761

# Comando para ejecutar la aplicación
ENTRYPOINT ["java", "-jar", "app.jar"]