# Product Service - Spring Boot Microservice

## Lab 3 - DevOps - SE4010 -IT22926630

This is a simple RESTful microservice built with Spring Boot that demonstrates:
- CRUD operations for Product management
- In-memory H2 database
- API documentation with Swagger/OpenAPI

## Project Details

- **Group**: com.sliit
- **Artifact**: product-service
- **Packaging**: jar
- **Java Version**: 17
- **Spring Boot Version**: 3.2.0

## Technologies Used

- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database (In-Memory)
- Springdoc OpenAPI UI (Swagger)
- Maven

## Prerequisites

- Java 17 or higher
- Maven 3.6+

## Running the Application

1. Navigate to the project directory:
```bash
cd product-service
```

2. Build the project:
```bash
mvn clean install
```

3. Run the application:
```bash
mvn spring-boot:run
```

The application will start on `http://localhost:8080`

## API Endpoints

### Product CRUD Operations

- **POST** `/api/products` - Create a new product
- **GET** `/api/products` - Get all products
- **GET** `/api/products/{id}` - Get product by ID
- **PUT** `/api/products/{id}` - Update a product
- **DELETE** `/api/products/{id}` - Delete a product


## H2 Database Console

Access the H2 database console at: `http://localhost:8080/h2-console`

**Connection Details:**
- **JDBC URL**: `jdbc:h2:mem:productdb`
- **Username**: `sa`
- **Password**: (leave empty)

## Swagger UI

Access the Swagger UI for API documentation and testing at:
- **Swagger UI**: `http://localhost:8080/swagger-ui.html`
- **API Docs (JSON)**: `http://localhost:8080/api-docs`





```
author - IT22926630
```

