# Use a base image containing Java runtime environment
FROM openjdk:17-jdk-alpine

# Set the working directory inside the container
#WORKDIR /app

# Copy the jar file generated by the Spring Boot build into the container
#COPY target/demo-app-post-0.0.1-SNAPSHOT.jar twit-app.jar

# Expose the port your application will run on
EXPOSE 8080

ADD target/twit-app-0.0.1-SNAPSHOT.jar twit-app.jar

# Command to run the application

ENTRYPOINT ["java", "-jar", "/twit-app.jar"]





