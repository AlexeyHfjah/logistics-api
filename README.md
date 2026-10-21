# LogisticsApi

REST API for managing trips in a small logistics company.

## Features

- Driver management
- Vehicle management
- Trip management and scheduling
- Prevention of overlapping trips for the same driver or vehicle
- Address suggestions through an external geocoding API

## Tech Stack

- C#
- .NET 10
- ASP.NET Core Web API
- Entity Framework Core
- PostgreSQL
- Docker Compose
- xUnit

## Project Structure

- `LogisticsApi.API` — HTTP endpoints and API configuration
- `LogisticsApi.BLL` — business logic
- `LogisticsApi.DAL` — data access and database configuration

## Prerequisites

- .NET 10 SDK
- Docker Desktop with Docker Compose

## Getting Started

1. Clone the repository.
2. Create a `.env` file in the repository root using `.env.example` as a template.
3. Set your local PostgreSQL credentials in `.env`.
4. Start the database:

   ```bash
   docker compose up -d
   ```

5. Run the API from Visual Studio or the .NET CLI.

Database migrations and API configuration will be added in subsequent development steps.

## Status

Work in progress.