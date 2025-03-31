# Chat Application - VTelegramme

A full-stack chat application consisting of a backend service and a frontend UI, built with Java (Spring Boot) and Angular. This project includes Dockerized services for both the backend and frontend, allowing for easy deployment.

## Project Structure

- **chat-service**: Spring Boot backend service that provides RESTful APIs and manages chat-related logic.
- **chat-web-ui**: Angular frontend that communicates with the backend and displays the chat interface.

## Requirements

- Docker
- Docker Compose

## Setup

1. Clone the repository:

   ```bash
   git clone --recurse-submodules https://github.com/yxngxr1/vtelegramme.git
   cd vtelegramme
   
2. Create a .env file in the current directory like .env.example

3. Build and run the services with Docker Compose:
   ```bash
   docker-compose up --build

### Accessing the Application
#### Frontend (UI): The frontend service will be running on http://localhost:4200 by default.
#### Backend (API): The backend service will be running on http://localhost:8080 by default.
#### PostgreSQL (DATABASE): The PostgreSQL service will be running on http://localhost:5432 by default.