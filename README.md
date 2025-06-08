# Microservices Tutorial

Learn Spring Boot CRUD operations, RestTemplate communication, and OAuth2 security.

## Services
- **User Management Service** (Port 8081) - Authorization Server
- **Product Catalog Service** (Port 8082) - Resource Server
- **Order Management Service** (Port 8083) - Resource Server

## Prerequisites
- Java 17+
- Maven 3.6+
- Git

## Getting Started
1. Clone the repository
2. Import each service in your IDE
3. Follow the implementation guide

## Running Services
```bash
# Terminal 1
cd user-management-service
mvn spring-boot:run

# Terminal 2  
cd product-catalog-service
mvn spring-boot:run

# Terminal 3
cd order-management-service  
mvn spring-boot:run