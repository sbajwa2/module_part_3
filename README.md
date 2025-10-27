# Pixel River Financial Bank Services - Module 5 Part 3

## Project Overview

This project implements a multi-language microservices banking application, including:

1. **Student Portfolio** – Static HTML front-end.
2. **Backend** – Python/Flask API microservice for banking operations (register, login, deposit, withdraw, dashboard).
3. **Transactions** – JavaScript microservice for viewing monthly user transactions.
4. **MongoDB** – Database for storing users and transactions.
5. **NGINX** – Reverse proxy to route traffic to frontend and backend services.

This setup also includes **CI/CD using GitHub Actions** and is deployable via **Docker Compose** and **Vagrant**.

---

## Directory Structure

```text
module5/part3/
├── backend/             # Flask API microservice
├── studentportfolio/    # Static HTML frontend
├── transactions/        # JavaScript microservice
├── docker-compose.yml   # Docker Compose file
├── nginx.conf           # NGINX configuration
└── .github/
    └── workflows/
        └── ci.yml       # GitHub Actions workflow
