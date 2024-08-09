# Minimal API - PizzaStore

This is a simple example of a Minimal API built with ASP.NET Core, showcasing basic CRUD operations for a Pizza Store. The project demonstrates how to set up an in-memory database, create a minimal API, and integrate Swagger for API documentation.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [License](#license)

## Features

- Minimal API structure using ASP.NET Core.
- Basic CRUD operations for managing a list of pizzas.
- In-memory database to store pizza information.
- Swagger integration for easy API testing and documentation.

## Getting Started

### Prerequisites

- [.NET 7 SDK](https://dotnet.microsoft.com/download/dotnet/7.0) or later
- An IDE or text editor (e.g., [Visual Studio](https://visualstudio.microsoft.com/), [Visual Studio Code](https://code.visualstudio.com/))

### Installation

1. Clone the repository:
   git clone https://github.com/Utsav-AD/minimalApi.git

2. Navigate to the project directory:
cd minimalApi

3. Restore the required packages:
dotnet restore

### Running the Application
 1. To run the application, use the following command:
dotnet run

The application will start, and you can access it via http://localhost:50** by default.

To view the Swagger UI for testing the API, navigate to http://localhost:50**/swagger.

### API Endpoints
The following endpoints are available in the API:

GET / - Returns a welcome message ("Hello World!").
GET /pizzas - Retrieves a list of all pizzas.
GET /pizzas/{id} - Retrieves a specific pizza by id.
POST /pizzas - Creates a new pizza.
PUT /pizzas/{id} - Updates an existing pizza by id.
DELETE /pizzas/{id} - Deletes a pizza by id.

### Technologies Used
.NET 7 - Framework for building the application.
ASP.NET Core - For building the web API.
Swagger / Swashbuckle - For API documentation and testing.

### Explanation:

- **Features**: Lists the core features of the project.
- **Getting Started**: Details the prerequisites, installation steps, and instructions to run the application.
- **API Endpoints**: Provides a brief overview of the available API endpoints with a sample request and response.
- **Technologies Used**: Lists the main technologies utilized in the project.
- **License**: Specifies the license under which the project is distributed.

This README provides a clear and concise overview of the project, making it easy for others to understand and contribute.

