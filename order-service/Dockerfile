# Step 1: Use an official OpenJDK image as a base image (Choose version based on your needs)
FROM openjdk:8-jdk-alpine

# Step 2: Set the working directory inside the container
WORKDIR /app

# Step 3: Copy the jar file into the container
# Assuming your Java app is built into a JAR file, change the filename if necessary
COPY target/order-service-0.0.1-SNAPSHOT.jar app.jar

# Step 4: Expose the port that the application will run on (e.g., port 8080 for Spring Boot)
EXPOSE 8813

# Step 5: Define the command to run the Java application
# Adjust the jar file name based on your actual jar file
CMD ["java", "-jar", "app.jar"]
