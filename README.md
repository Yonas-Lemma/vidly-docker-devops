# Vidly Dockerized Application

This project is a Dockerized version of the **Vidly** application, which includes:

- **Frontend**: A React application for the user interface.
- **Backend**: A Node.js/Express API for managing movies.
- **Database**: A MongoDB database for data storage.

The application is fully containerized using Docker and orchestrated with Docker Compose.

---

## Project Structure

- **frontend/**: React application.
  - **Dockerfile**: Located at `frontend/Dockerfile`.
- **backend/**: Node.js/Express API.
  - **Dockerfile**: Located at `backend/Dockerfile`.
- **docker-compose.yml**: Orchestrates the services.

---

## Docker Images

### 1. **Frontend (React)**

- **Dockerfile Location**: `frontend/Dockerfile`
- **Base Image**: `node:14.16.0-alpine3.13`
- **Exposed Port**: `3000`
- **Purpose**: Builds and runs the React application in development mode.

### 2. **Backend (Node.js/Express)**

- **Dockerfile Location**: `backend/Dockerfile`
- **Base Image**: `node:14.16.0-alpine3.13`
- **Exposed Port**: `3001`
- **Purpose**: Builds and runs the Node.js backend API.

### 3. **Database (MongoDB)**

- **Image**: `bitnami/mongodb:latest`
- **Configuration**: Defined in `docker-compose.yml` under the `db` service.
- **Exposed Port**: `27017`
- **Purpose**: Provides a MongoDB database for the application.

---

## Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
<img width="3760" height="2210" alt="compose-run" src="https://github.com/user-attachments/assets/f4abaac0-019d-4e4c-b9aa-88b81a07d55b" />
<img width="1850" height="1040" alt="app" src="https://github.com/user-attachments/assets/dca46a4d-1537-4efa-9f78-e83d38a16b13" />

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Yonas-Lemma/vidly-docker-devops.git
cd vidly-dockerized
![Uploading image.png…]()
