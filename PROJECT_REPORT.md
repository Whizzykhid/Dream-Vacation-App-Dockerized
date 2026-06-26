# Deployment Notes

## Implementation

This repository was containerized using Docker and Docker Compose.

The following tasks were completed:

- Created Dockerfiles for the frontend and backend services.
- Configured a multi-container application using Docker Compose.
- Added a PostgreSQL database service with a health check.
- Configured persistent database storage using Docker volumes.
- Configured Nginx to serve the React frontend.
- Connected the frontend, backend, and database through Docker networking.
- Successfully built and deployed the application using Docker Compose.

> **Note:** The backend application logic (`server.js`) was provided as part of the assignment and was not modified.

---

## Running the Application

Clone the repository and start the application with:

```bash
docker compose up --build
```

Once the containers are running, the application is available at:

- **Frontend:** http://localhost:8080
- **Backend API:** http://localhost:3001

---

## Screenshots

### Project Structure

![Project Structure](screenshots/01-project-structure.png)

### Docker Compose Build

![Docker Compose Build](screenshots/02-docker-compose-building.png)
![Docker Compose Running](screenshots/02-docker-compose-running.png)

### Running Containers

![Docker PS](screenshots/03-containers-running.png)

### Application Running

![Application Running](screenshots/04-application-running.png)

### Backend Running

![Backend Running](screenshots/05-backend-running.png)