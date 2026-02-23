<div align="center">
<a href="https://github.com/fahmirizalbudi/casheex" target="blank">
<img src="https://raw.githubusercontent.com/JjagoKoding/icon/6a2daacc5ac3dc9ccae1dad4a5f503e55af42c3f/casheex.svg" width="300" alt="Logo" />
</a>

<br />
<br />

![](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![](https://img.shields.io/badge/Gin-00A393?style=for-the-badge&logo=gin&logoColor=white)
![](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

</div>

<br/>

## Casheex

Casheex is a RESTful API designed for point-of-sale (POS) systems, providing essential backend functionality for retail and small business environments. Developed using the Go programming language and the Gin web framework, this project serves as a technical implementation for managing transactions and inventory with MySQL for persistent data storage.

## Features

- **Product and Inventory Management:** Standardized endpoints for cataloging, updating, and tracking inventory items.
- **Transaction Processing:** Robust logic for handling checkout operations, including automated total calculations.
- **Sales Reporting:** Structured logging of transaction data to facilitate business analysis and sales history retrieval.

## Tech Stack

- **Go**: A statically typed, compiled programming language optimized for high-performance concurrent systems.
- **Gin**: A high-performance HTTP web framework for Go, utilized for its efficiency in building RESTful APIs.
- **MySQL**: A relational database management system employed for secure and structured data persistence.

## Getting Started

Follow these procedures to deploy a local instance of the Casheex API.

### Prerequisites

- **Go** (v1.24.x or higher).
- **MySQL** (or a compatible SQL database).

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/fahmirizalbudi/casheex.git
   cd casheex
   ```

2. **Initialize Dependencies:**

   ```bash
   go mod tidy
   ```

3. **Configure Database:**
   Ensure your MySQL instance is active and configure the connection string within the application's configuration or environment variables.

4. **Execute the Application:**

   ```bash
   go run main.go
   ```

## Usage

### Execution Modes

- **Development:** `go run main.go`
- **Production Build:**
  ```bash
  go build -o casheex main.go
  ./casheex
  ```

The API service is hosted locally at [http://localhost:8080](http://localhost:8080).

### API Documentation

Comprehensive endpoint specifications and usage guidelines are accessible via the Swagger/OpenAPI documentation at [http://localhost:8080/api/docs](http://localhost:8080/api/docs).

## License

All rights reserved. This project is intended for educational purposes and may not be utilized or distributed without explicit authorization.
