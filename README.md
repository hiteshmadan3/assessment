
# Spring Boot Banking Project

This is a Spring Boot application designed for a banking system. It follows a typical layered architecture and demonstrates the use of various components in a banking system, including controllers, services, repositories, and models.

## Project Structure

- **controller**: Contains REST controllers that handle incoming HTTP requests and return responses to the client.
- **model**: Defines the domain objects representing entities in the banking system (e.g., Account, Customer, Transaction).
- **repository**: Contains interfaces for interacting with the database, using Spring Data JPA.
- **service**: Contains business logic that processes data and performs operations on the entities.
- **resources**: Includes configuration files and templates used by the application.
- **pom.xml**: The Maven build file that manages dependencies and builds the application.

## Setup

1. Clone the repository or download the project files.
2. Navigate to the project directory.
3. Run the following command to build and run the project:

```bash
mvn spring-boot:run
```

4. The application should now be accessible at `http://localhost:8080`.

## Endpoints

- **GET /accounts**: Retrieves all accounts.
- **POST /accounts**: Creates a new account.
- **GET /accounts/{id}**: Retrieves an account by its ID.
- **POST /transactions**: Initiates a transaction.

## Technologies Used

- Spring Boot
- Spring Data JPA
- Maven
- H2 Database (or your preferred database)

## Setup in new System
This setup is done in MyLocal can change in other machine so put dependency accordingly to run the Project.

