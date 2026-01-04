# Spring Boot Microservices – POC

## Overview
This is a **Proof of Concept (POC)** demonstrating a microservices architecture
using **Spring Boot** and **Spring Cloud**. The project showcases how independent services
communicate via **REST** and **RabbitMQ**, with **centralized configuration**, **service discovery**, 
and **API routing** through a gateway.

**Swagger UI** is used for API documentation and **Docker** is used for containerized deployment.

---

## Services & Components
- **Employee Service** – Manages employee data  
- **Department Service** – Manages department data  
- **Organization Service** – Manages organization information  
- **Config Server** – Centralized configuration  
- **Service Registry (Eureka)** – Service discovery  
- **API Gateway** – Request routing and aggregation  
- **RabbitMQ** – Asynchronous messaging  
- **Swagger UI** – Interactive API documentation  

---

## Tech Stack
- **Java 17+**, **Spring Boot**, **Spring Cloud**  
- **Eureka** – Service discovery  
- **Spring Cloud Config** – Centralized configuration  
- **Spring Cloud Gateway** – API routing  
- **RabbitMQ** – Messaging  
- **Swagger / OpenAPI** – API docs  
- **Docker & Docker Compose** – Containerization  

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/spring-boot-microservices-poc.git
cd spring-boot-microservices-poc
