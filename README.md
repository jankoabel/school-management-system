# School Management System with ASP.NET Core 7 MVC


The project is a supporting repository for the course called "ASP.NET Core 7 MVC - Cross-Platform Development.
## Table of Contents

- [School Management System with ASP.NET Core 7 MVC](#school-management-system-with-aspnet-core-7-mvc)
  - [Table of Contents](#table-of-contents)
  - [Technologies](#technologies)
  - [Getting Started](#getting-started)
  - [Project Structure](#project-structure)
  - [Features](#features)
  - [Documentation](#documentation)

## Technologies

The project uses the following technologies:

- ASP.NET Core 7 MVC
- Entity Framework Core
- SQL Server
- Bootstrap
- jQuery
- AutoMapper

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the latest version of .NET Core SDK and SQL Server on your machine.
3. Update the connection string in the `appsettings.json` file with your SQL Server connection string.
4. Run the following commands in the root directory of the project to set up the database: `dotnet ef database update --project SchoolManagementSystem.Infrastructure --startup-project SchoolManagementSystem.Web`
5. Run the following command to start the web application: `dotnet run --project SchoolManagementSystem.Web`


## Project Structure

The solution is composed of the following projects:

- `SchoolManagementSystemApp`: Contains the MVC controllers, views, and data models.

## Features

The project includes the following features:

- Authentication and Authorization using OAuth and cookies
- CRUD operations for Students, Teachers, and Classes
- Search functionality for Students and Teachers
- Form Validation
- Exception handling middleware

## Documentation

The repository contains documentation for each of the features, including:

- An overview of the feature and its intended use case
- Installation and configuration instructions
- Code walkthroughs and explanations
- Best practices and tips for working with the feature





