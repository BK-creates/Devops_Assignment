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

![Project Structure]![Image](https://github.com/user-attachments/assets/4034cda9-f529-4843-b261-71694c8a831e)

