# Simple ASP.NET Core Web API Project

## Overview

This project is a web API built with **ASP.NET Core** as part of the [Microsoft Learn Module](https://learn.microsoft.com/en-us/training/modules/build-web-api-aspnet-core/). It demonstrates how to build a RESTful API with ASP.NET Core, allowing CRUD operations through HTTP requests.

## Features

- RESTful API with routes for retrieving, creating, updating, and deleting data.
- Create an in-memory database for persisting products.
- Implements **Entity Framework Core** for data persistence.
- Follows **MVC architecture** (Model-View-Controller) principles for separation of concerns.
- Uses **Swagger/OpenAPI** for documentation and testing endpoints.
- Test web API action methods from the command shell.
  
## Requirements

- **.NET SDK 6.0** or later
- **Visual Studio 2022** or another IDE with .NET Core support
- **SQL Server** or any supported database for data persistence

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/arsescode/simple-dotnet-api.git
    cd simple-dotnet-api
    ```

2. Restore dependencies:
    ```bash
    dotnet restore
    ```
3. Build and run the application:
    ```bash
    dotnet run
    ```

## Running the API

Once the application is running, you can test the API using tools like **Postman**, **Curl**, or the built-in **Swagger UI** by navigating to `http://localhost:{port}/swagger` in your browser.

## Test the finished web API with HTTP files

1. open the DotnetAPI.http file in **Visual Studio Code** or **Visual Studio 2022**.
2. click **Send Request** above each test to see result.

## Contributing

Feel free to submit issues or pull requests if you'd like to contribute to this project.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.
