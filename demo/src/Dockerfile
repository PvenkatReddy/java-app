# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the project jar file to the container
COPY target/java-docker-app-1.0-SNAPSHOT.jar /app/app.jar

# Expose the port where the app runs
EXPOSE 8080

# Run the Java application
ENTRYPOINT ["java", "-jar", "/app/app.jar"]
