
---

## 6. `book-service`

**Repository About description:**  
> REST API for managing book inventory (CRUD operations) using MySQL. Part of Library Management System.

```markdown
# Book Service

## Mandatory Information

- **Student Name**: [B.K.Harsha Nimeda Sirithunga]
- **Student Number**: [2301691058]
- **Slack Handle**: [@Harsha Nimeda]
- **GCP Project ID**: [indigo-splice-491917-q2]

## Project Description

The **Book Service** handles all book-related operations in the Library Management System. It provides REST endpoints to create, read, update, and delete books. The service uses **MySQL** as its database and registers itself with Eureka for discovery. It also exposes an internal endpoint to update available copies when a book is borrowed or returned.

## Technology Stack

- Java 25
- Spring Boot 3.4.5
- Spring Data JPA (Hibernate)
- MySQL Connector
- Spring Cloud Netflix Eureka Client
- Spring Cloud Config Client
- Spring Boot Actuator

## Setup / Getting Started Instructions

### Prerequisites
- Java 25
- Maven
- MySQL (running locally)
- Config Server (port 8888)
- Eureka Server (port 8761)

### Database Setup

Create the database:

```sql
CREATE DATABASE book_db;
