#DevOps Assignment: Multi-Service App with Docker & Nginx

This project demonstrates how to build and orchestrate a simple microservice-based architecture using **Docker Compose**, with **Nginx** as a reverse proxy.

It includes two backend services:
- A **Go (Golang)** service (`service-1`)
- A **Python Flask** service (`service-2`)

Nginx routes requests to each service based on the request path, all accessible via `localhost:8080`.



## ⚙️ How to Run the Project

> Requires Docker & Docker Compose installed.

1. Clone the repo or download the project
2. In the project root, run:

```bash
docker-compose up --build
## Screenshots

![Project Structure]

