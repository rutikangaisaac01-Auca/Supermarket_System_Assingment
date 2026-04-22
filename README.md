# Supermarket_System_Assignment

This project is a Java-based OOP application that has been packaged into a JAR file and set up to run using Docker.

## Project Contents
- app.jar (compiled Java application)
- Dockerfile (used to containerize and run the app)

## Running the Application

### Run with Java
java -jar app.jar

### Run with Docker
docker build -t supermarket-app .
docker run supermarket-app
