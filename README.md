# Library Management System

A production-style Spring Boot microservices application for managing
books, users, loans, notifications, and audit events.

## Tech Stack

- Java 25
- Spring Boot 4.1.1
- Spring Cloud
- Spring Security
- JWT
- MySQL
- Apache Kafka
- OpenFeign
- Eureka
- Spring Cloud Gateway
- Resilience4j
- Docker
- Kubernetes
- AWS
- Terraform
- GitHub Actions
- JUnit 5
- Mockito
- Testcontainers

## Microservices

- Config Server
- Service Discovery
- API Gateway
- Auth Service
- User Service
- Book Service
- Loan Service
- Notification Service
- Audit Service

## Architecture

Client
  ↓
API Gateway
  ↓
Microservices
  ↓
MySQL

Loan Service
  ↓
Kafka
  ↓
Notification Service
  ↓
Audit Service
