# Task-Manager-API

A secure RESTful API for managing tasks, built with ASP.NET Core. Includes JWT authentication, role-based access control, and Redis-backed token blacklisting.

## Features

- **User Management**
  - Registration/login with BCrypt password hashing
  - Role-based authorization (Admin/User)
  - Profile updates and account deletion

- **Task Operations**
  - Create, read, update, and delete tasks
  - Pagination and filtering (by status/priority)
  - Ownership validation with admin overrides

- **Security**
  - JWT authentication with refresh tokens
  - Redis token blacklisting for secure logout
  - AutoMapper-protected DTOs to prevent over-posting

- **Infrastructure**
  - Entity Framework Core (SQL Server)
  - Clean architecture (Controllers → Services → Repository)
  - Swagger/OpenAPI documentation

## Tech Stack

**Backend:**  
- .NET 8
- ASP.NET Core Web API
- Entity Framework Core
- AutoMapper

**Security:**  
- JWT Bearer Authentication
- BCrypt.Net-Next
- Redis (token blacklist)

**Tools:**  
- Swagger UI
- MS SQL Server
