# Simply Fly - Air Ticket Booking System (Spring Boot)
A secure backend system for booking and managing flights, built using Java and Spring Boot. It supports three roles: Admin, Flight Owner, and User, all authenticated with JWT.

## Core Features
1. User: Register, login, search flights, book tickets, view/update profile

2. Flight Owner: Add/manage flights they own

3. Admin: Full control – manage users, routes, flights, and bookings

## JWT Authentication: Role-based secure access

## Swagger UI: Interactive API testing

## Tech Stack
- Java 17, Spring Boot, Spring Security

- JWT (stateless auth), MySQL, JPA (Hibernate)

- Swagger (OpenAPI 3) for documentation

## Key Packages

1. controller – API endpoints
2. dto – Request & response data structures
3. entity – Database models (User, Flight, Booking, etc.)
4. service – service interface
5. service implementation - Business logic
6. repository – Data access (JPA)
7. security – JWT utilities & filters
8. config – App & Swagger configuration
9. exception -  custom exceptions and global exception handler

## Sample Roles & Users

1. Admin: admin@example.com / Admin@123
2. Flight Owner: flightowner@example.com / flightowner@123
3. User: srimathi@example.com / sri@123

## API Documentation
Access via Swagger UI:
📍 http://localhost:8081/swagger-ui/index.html

## Use Authorize (🔑 icon) with: Bearer token
