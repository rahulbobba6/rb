# Use an official Java runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file from the host to the container
COPY /var/lib/jenkins/workspace/rav/Monolithic/target/Monolithic-0.0.1-SNAPSHOT.jar /app/myapp.jar

# Expose the application port (if applicable)
EXPOSE 1432

# Command to run the application
CMD ["java", "-jar", "myapp.jar"]
