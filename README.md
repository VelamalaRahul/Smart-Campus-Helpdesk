🚀 Smart Campus Helpdesk API
📌 Description

Smart Campus Helpdesk API is a production-style RESTful backend system built using Django REST Framework. It enables students to raise support tickets and administrators to manage campus issues efficiently.

The system implements JWT authentication, PostgreSQL integration, dynamic filtering, search, ordering, pagination, and response caching, demonstrating scalable backend architecture, secure API development, and clean design principles.

This project follows RESTful standards and structured backend development practices suitable for real-world applications.

🛠 Tech Stack

Python

Django

Django REST Framework

PostgreSQL

JWT (SimpleJWT)

Django Cache Framework

⚙️ Key Features

🔐 JWT-based Authentication
🎫 Full CRUD Ticket Management
🔎 Search & Filtering (category, status)
↕ Ordering (priority, created date)
📄 Pagination Support
⚡ Caching for Optimized Performance
🛡 Session Authentication for Admin Panel
🗃 PostgreSQL Database Integration
📦 Structured and Modular Project Architecture
🧩 Query Parameter-Based Dynamic API Responses
🛠 Admin Dashboard Customization

🏗 Project Flow
User Login → JWT Token Generated → Authenticated API Access
        ↓
Request → Filtering / Search / Ordering
        ↓
Pagination → Response Returned
        ↓
GET responses cached (60 seconds)
POST/PATCH/DELETE → Cache Cleared for Data Consistency
🔑 Main Endpoints
POST   /api/token/
POST   /api/token/refresh/

GET    /tickets/
POST   /tickets/
GET    /tickets/{id}/
PATCH  /tickets/{id}/
DELETE /tickets/{id}/
🧠 Backend Concepts Demonstrated

REST API Design

Authentication & Authorization

Database Connectivity

Query Optimization

Pagination Handling

Cache Invalidation Strategy

Clean Code & Modular Architecture

Production-Style Backend Development

👨‍💻 Author

Rahul Velamala
Backend Developer | Django REST Framework
