# Spring & Angular Chatbot Application with Docker

This project is a full-stack chatbot application built using **Angular** for the frontend and **Spring Boot** for the backend. The application connects to a **PostgreSQL** database and is fully containerized using **Docker** and **Docker Compose**. It demonstrates modern DevOps practices and microservices deployment.

## 🧩 Project Structure

├── backend/ # Spring Boot application 

├── frontend/ # Angular application 

├── postgres/ # PostgreSQL database setup 

├── docker-compose.yml # Multi-container orchestration 

└── README.md

## 🚀 Features

- Chatbot frontend built with Angular
- RESTful backend using Spring Boot
- PostgreSQL integration for persistent storage
- Dockerized frontend, backend, and database
- Docker Compose for easy multi-container setup
- Microservices-ready architecture (optional extension)

## 🛠️ Technologies Used

- Angular
- Spring Boot
- PostgreSQL
- Docker
- Docker Compose

## ⚙️ Setup & Installation

### Prerequisites

- Docker installed on your machine
- Docker Compose installed

### Running the Application

To start all services (frontend, backend, and database), run:

```bash
docker-compose up --build
