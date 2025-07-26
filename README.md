# 🧩 Microservices Architecture Project

A scalable and modular backend system built with Spring Boot and MongoDB, deployed using Docker and AWS. This architecture separates concerns across multiple services to ensure flexibility, maintainability, and performance.

## 🛠 Tech Stack

- **Spring Boot** – RESTful microservices with separate modules for auth, user, and data processing
- **MongoDB** – NoSQL database for storing user and domain data
- **Docker** – Containerization for simplified deployment and scaling
- **AWS** – Cloud infrastructure setup using EC2, S3, and ECS

## 📦 Services

| Service        | Description                                 | Port |
|----------------|---------------------------------------------|------|
| Auth Service   | Handles JWT-based authentication             | 8081 |
| User Service   | Manages user profiles and registration       | 8082 |
| Data Service   | Processes and stores domain-specific logic   | 8083 |

## 📂 Folder Structure

```bash
├── auth-service/
├── user-service/
├── data-service/
├── docker-compose.yml
├── README.md
