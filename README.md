# Enterprise Workflow Management System

A production-ready Enterprise Workflow Management System built using Java, Spring Boot, MySQL and JWT Authentication. The application helps organizations manage employee workflows, departments, attendance, leave requests, inventory operations and role-based access control through secure REST APIs.

---

## Features

### Authentication & Security
- JWT-based Authentication
- Role-Based Authorization (Admin, HR, Finance, Inventory)
- Secure Password Encryption using Spring Security
- Protected REST APIs

---

## Admin Module
- Create, Update and Delete Users
- Assign Roles & Permissions
- Activate/Deactivate Accounts
- Reset User Passwords
- Department-wise User Management

---

## HR Management
- Employee Management
- Leave Request & Approval Workflow
- Attendance Management
- Payroll Management
- Performance Tracking

Attendance Status:
- PRESENT
- ABSENT
- LEAVE
- NOT_MARKED

---

## Inventory Management
- Product Inventory Tracking
- Stock Management
- Purchase Order Handling

---

## Finance Module
- Salary Processing
- Payroll Operations
- Financial Data Management

---

## Technical Features
- RESTful APIs
- DTO-Based Architecture
- Layered Architecture
- Global Exception Handling
- Validation Handling
- Secure Authentication & Authorization

---

## Tech Stack

- Java 17
- Spring Boot
- Spring Security
- Spring Data JPA
- MySQL
- JWT Authentication
- Maven
- Lombok

---

## Project Structure

```text
src
├── config            → Security & JWT Configuration
├── controller        → REST API Controllers
├── dto               → Data Transfer Objects
├── entity            → Database Entities
├── repository        → JPA Repositories
├── request           → Request Models
├── response          → API Responses
├── service           → Business Logic
└── service/impl      → Service Implementations
```

## Getting Started

### Prerequisites
- Java 17+
- MySQL
- Maven

---

### Database Setup

```sql
CREATE DATABASE erp_db;