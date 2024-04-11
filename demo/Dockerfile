FROM adoptopenjdk/openjdk11:alpine-jre

# Set working directory in the container
WORKDIR /app

# Copy the compiled Spring Boot application JAR file into the container
COPY target/demo-0.0.1-SNAPSHOT.jar /app/demo.jar

# Expose port 8080
EXPOSE 8080

# Command to run the Spring Boot application
CMD ["java", "-jar", "demo.jar"]