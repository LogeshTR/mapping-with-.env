# Use an official OpenJDK runtime as a base image
FROM openjdk:11-jre-slim

# Set the working directory in the container
WORKDIR /app

# Copy the application JAR file into the container at /app
COPY target/your-spring-boot-app.jar /app/app.jar

# Expose the port that the application will run on
EXPOSE 8080

# Specify the command to run on container start
CMD ["java", "-jar", "app.jar"]
