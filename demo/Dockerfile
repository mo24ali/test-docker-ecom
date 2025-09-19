# Use OpenJDK base image
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy JAR file
COPY target/backend.jar backend.jar

# Expose port
EXPOSE 8080

# Run the app
ENTRYPOINT ["java", "-jar", "backend.jar"]
