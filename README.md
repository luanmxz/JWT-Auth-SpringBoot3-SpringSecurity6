# JWT Auth Spring Boot 3 & Spring Security 6

This project is a small practice project for JWT Authentication and Authorization using Spring Boot 3 and Spring Security 6.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Endpoints](#endpoints)
- [License](#license)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/luanmxz/JWT-Auth-SpringBoot3-SpringSecurity6.git
    cd JWT-Auth-SpringBoot3-SpringSecurity6
    ```

2. Build the project using Maven:

    ```bash
    ./mvnw clean install
    ```

## Usage

1. Run the application:

    ```bash
    ./mvnw spring-boot:run
    ```

2. The backend server will start, and you can access it at `http://localhost:8080`.

## Project Structure

- **src/**: Contains the source code
  - **main/**: Main application files
    - **java/**: Java source files
    - **resources/**: Application properties and configuration
  - **test/**: Test files

## Endpoints

- **POST /auth/login**: Authenticate user and generate JWT.
- **GET /users**: Retrieve a list of users (protected endpoint).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
