# Leave Management System

This repository contains the source code for a .NET Core Leave Management System built using Clean Architecture. The project uses CQRS, AutoMapper, Blazor, .NET API, and EF Core. It also includes unit and integration tests both.

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









