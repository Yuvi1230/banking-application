# Banking Application

A comprehensive banking application designed using HTML, CSS, Thymeleaf for the frontend, and Java with Spring Boot for the backend. This application enables users to perform essential banking operations such as managing accounts, making transactions, and viewing transaction histories.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization
- Account management (create, update, delete accounts)
- Transaction processing (deposits, withdrawals, transfers)
- View account balances and transaction history
- Responsive design with a user-friendly interface

## Tech Stack

- **Frontend:** HTML, CSS, Thymeleaf
- **Backend:** Java, Spring Boot
- **Database:** MySQL (or your preferred database)
- **API Documentation:** Swagger (for detailed API specs)

## Architecture

The application follows a client-server architecture:
- **Frontend:** Built with HTML, CSS, and Thymeleaf, responsible for rendering the UI with dynamic content.
- **Backend:** Built with Java and Spring Boot, responsible for handling business logic and communicating with the database.

## Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

- Java JDK 11 or higher
- Maven (for managing Java dependencies)
- MySQL (or other preferred database)

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd banking-application
   ```
2. **Backend Setup:**

   ```bash
   mvn clean install

   ```

3. **Database Setup:**
   - Create a database named `banking_app`.
   - Update the database credentials in the `src/main/resources/application.properties` file.
     
4. **Run the Application:**

   ```bash
   mvn spring-boot:run

   ```


## Usage
- Access the application at `http://localhost:8080`.
- Use the login page to access your account.
- Navigate through the application to perform banking operations.

## API Endpoints

| Method | Endpoint                | Description                    |
|--------|-------------------------|--------------------------------|
| GET    | `/api/accounts`         | Fetch all user accounts        |
| POST   | `/api/accounts`         | Create a new account           |
| PUT    | `/api/accounts/{id}`    | Update account details         |
| DELETE | `/api/accounts/{id}`    | Delete an account              |
| POST   | `/api/transactions`     | Perform a transaction (deposit, withdrawal, transfer) |

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any changes you propose.

