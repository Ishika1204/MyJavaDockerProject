# Use OpenJDK 11 runtime
FROM openjdk:11-jre-slim

# Copy the built JAR file from Maven target folder
COPY target/*.jar app.jar

# Run the JAR
ENTRYPOINT ["java", "-jar", "app.jar"]
