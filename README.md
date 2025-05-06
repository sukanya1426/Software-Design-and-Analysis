# 🧑‍💼 User Management System with Role

A Spring Boot 3.x application implementing **Clean Architecture** principles to manage users and their role assignments. Built with a strong separation of concerns, this project ensures scalability, maintainability, and clarity between business logic and infrastructure.

## 🚀 Key Features

### 👤 Core Functionality
- **User Operations**: Create and retrieve user records
- **Role Management**: Define and maintain system roles
- **Role Assignment**: Associate roles with users
- **Data Validation**: Enforce proper email formats and required fields

### 🏛️ Architectural Highlights
- **Clean Architecture**: Strict separation of `domain`, `application`, and `infrastructure` layers
- **Database Support**: H2 in-memory database with web console access (`/h2-console`)
- **REST API**: Well-documented endpoints for user and role operations
- **Error Handling**: Returns meaningful HTTP status codes and clear error messages

## 🛠️ Technical Specifications
- **Framework**: Spring Boot 3.x
- **Language**: Java 17
- **Database**: H2 (in-memory, ephemeral)
- **Design Patterns**: 
  - DTO (Data Transfer Object) pattern for API contracts
  - Follows Clean Architecture dependency rules
- **Validation**: Input validation using Java Bean Validation (JSR 380)

---

## 📦 Getting Started

### ✅ Prerequisites
- Java 17
- Maven 3.8+

### ▶️ Running the Application

Clone the repo and run the app using Maven:

```bash
git clone https://github.com/sukanya1426/Software-Design-and-Analysis.git
cd user-management-system
./mvnw spring-boot:run
