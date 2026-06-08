# ShopFlow Backend

A microservices-based e-commerce backend built with Java 17, Spring Boot 3.x, and Spring Cloud.

## Architecture

- **API Gateway:** Spring Cloud Gateway (Port 8080)
- **Service Discovery:** Netflix Eureka (Port 8761)
- **Services:**
  - User Service (Authentication & Profile)
  - Product Service (Catalog Management)
  - Order Service (Order Processing)
  - Notification Service (Email/Push)
- **Databases:** PostgreSQL, MongoDB
- **Messaging:** RabbitMQ
- **Observability:** Zipkin, ELK Stack

## Quick Start

### Prerequisites
- Java 17+
- Maven 3.8+
- Docker & Docker Compose

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/ajay9009/shopflow-backend.git
   cd shopflow-backend