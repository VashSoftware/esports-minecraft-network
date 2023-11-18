# Use an existing Java Docker image
FROM openjdk:8-jdk-alpine

# Copy the Tekkit.jar file into the Docker image
COPY Tekkit.jar /usr/app/Tekkit.jar

# Set the working directory
WORKDIR /usr/app

# Expose the necessary port(s) for the Tekkit server
EXPOSE 25565

# Define the command to run the Tekkit server
CMD ["java", "-Xmx3G", "-Xms2G", "-jar", "Tekkit.jar", "nogui"]