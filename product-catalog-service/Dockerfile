# Step 1: Use an official OpenJDK image as a base image (Choose version based on your needs)
FROM openjdk:17-jdk-slim

# Step 2: Set the working directory inside the container
WORKDIR /app

# Step 3: Copy the jar file into the container
# Assuming your Java app is built into a JAR file, change the filename if necessary
COPY .  /app.jar

# Step 4: Expose the port that the application will run on (e.g., port 8080 for Spring Boot)
EXPOSE 8810

# Step 5: Define the command to run the Java application
# Adjust the jar file name based on your actual jar file
CMD ["java", "-jar", "app.jar"]
