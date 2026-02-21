# Use official Java runtime
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy jar file from target folder
COPY target/majorproj-1.0-SNAPSHOT.jar app.jar

# Expose port (only needed if app runs on port)
EXPOSE 8080

# Run the jar
ENTRYPOINT ["java", "-jar", "app.jar"]
