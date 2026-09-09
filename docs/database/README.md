# Database Strategy

## Database

MySQL 8.4

## Local Database

Database name:

library_db

## Connection

Host: localhost
Port: 3306
Database: library_db

## Microservice Database Ownership

Each microservice should own and manage its data.

Planned services:

- User Service
- Auth Service
- Book Service
- Loan Service
- Notification Service
- Audit Service

## Rules

1. A service must not directly modify another service's database tables.
2. Services communicate using REST/OpenFeign or Kafka.
3. Database credentials must not be committed to Git.
4. Production credentials must be provided through environment variables or secrets.
5. Database schema changes should be version-controlled.