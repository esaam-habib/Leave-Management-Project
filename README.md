# 🗓️ Leave Management System

A comprehensive **Leave Management System** built with **C#**, **.NET Core**, and **Entity Framework** that streamlines the leave request and approval process for organizations. The system follows **SOLID principles**, improves operational efficiency, and reduces manual errors with automated tracking and workflows.

---

## 🔧 Features

- ✅ Employee Leave Request Creation
- 🧾 Manager Approval Workflows
- 🗓️ Leave History and Status Tracking
- 🛠️ Admin Panel for Leave Configuration
- 🔐 Role-Based Access Control (Employees / Managers / Admin)
- ♻️ Automatic Leave Balance Updates
- 🧱 Designed with **SOLID principles** for maintainability

---

## 📦 Tech Stack

| Component        | Technology                      |
|------------------|----------------------------------|
| Backend Language | C#                               |
| Framework        | ASP.NET Core                     |
| ORM              | Entity Framework Core            |
| Database         | SQL Server / SQLite              |
| Architecture     | Layered Architecture (with Repositories & Services) |
| Auth & Security  | ASP.NET Identity / JWT / Role-based Authorization |
| Design Principles| SOLID, Clean Code, DRY, KISS     |

---

## 🧠 System Design

### Modules:
- **Employee Module**: Submit/view leave requests
- **Manager Module**: Approve or reject leave requests
- **Admin Module**: Configure leave types, reset balances, view reports


## Table of Contents

- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Code Samples](#code-samples)


## Technologies

The project uses the following technologies:

- .NET Core (6/7/8)
- CQRS
- AutoMapper
- Blazor
- .NET API
- EF Core
- xUnit
- MOQ

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Open the solution file in Visual Studio or another IDE of your choice.
3. Restore the NuGet packages.
4. Set the startup projects to `LeaveManagement.Api` and `LeaveManagement.BlazorUI`.
5. Run the project.

## Project Structure

The project is organized using the Clean Architecture principles. The solution is composed of the following projects:

- `LeaveManagement.Application`: Contains the application layer of the project, which contains the application logic and interfaces.
- `LeaveManagement.Domain`: Contains the domain layer of the project, which contains the domain models and business rules.
- `LeaveManagement.Infrastructure`: Contains the infrastructure layer of the project, which contains the implementation of the interfaces defined in the application layer.
- `LeaveManagement.Api`: Contains the API layer of the project
- `LeaveManagement.BlazorUI`: Contains the Blazor client application

## Code Samples

The project contains code samples for several areas of .NET Core development, including:

- CQRS
- AutoMapper
- Blazor
- .NET API
- EF Core
- Unit Testing
- Integration Testing

## 🔐 Authentication & Authorization
Role-based authorization implemented

Secure endpoints for employee, manager, and admin roles

Password hashing and secure login using ASP.NET Identity

## 👨‍💻 Author

Developed by Esaam Habib









