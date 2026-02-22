# Use OpenJDK 17
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy Maven build output
COPY target/payment-service.jar app.jar

# Expose port your service runs on
EXPOSE 8080

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
