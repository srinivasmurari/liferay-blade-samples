# Use a base image with a Java runtime environment
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container
COPY build/libs/*.jar /app/

# Define the command to run your application
CMD ["java", "-jar", "your-app.jar"]
