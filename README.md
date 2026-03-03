# Spring_Boot_App_Backend

This is a containerized Spring Boot application managed with Docker Compose.
Follow the steps below to run the application locally.

## Prerequisites
- Install [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- Ensure Docker Desktop is running

## Running the Application

1. Open a terminal and navigate to the directory containing `docker-compose.yaml`

2. Start the application:
   ```
   docker compose up -d
   ```
3. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```
4. To stop and remove the containers:
   ```
   docker compose down
   ```
5. To stop the containers and remove associated volumes (this deletes persisted data):
   ```
   docker compose down -v
   ```
