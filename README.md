# Simply Fly - Air Ticket Booking System (Spring Boot)
A secure backend system for booking and managing flights, built using Java and Spring Boot. It supports three roles: Admin, Flight Owner, and User, all authenticated with JWT.

🔑 Core Features
User: Register, login, search flights, book tickets, view/update profile

Flight Owner: Add/manage flights they own

Admin: Full control – manage users, routes, flights, and bookings

JWT Authentication: Role-based secure access

Swagger UI: Interactive API testing

🔧 Tech Stack
Java 17, Spring Boot, Spring Security

JWT (stateless auth), MySQL, JPA (Hibernate)

Swagger (OpenAPI 3) for documentation

📂 Key Packages
controller – API endpoints

dto – Request & response data structures

entity – Database models (User, Flight, Booking, etc.)

service – Business logic

repository – Data access (JPA)

security – JWT utilities & filters

config – App & Swagger configuration

👥 Sample Roles & Users
👤 Admin: admin@example.com / Admin@123

🧑‍✈️ Flight Owner: owner@example.com / owner@123

🙋‍♀️ User: srimathi@example.com / sri@123

🌐 API Documentation
Access via Swagger UI:
📍 http://localhost:8081/swagger-ui/index.html

Use Authorize (🔑 icon) with: Bearer <token>
