# Spring Boot MVC CRUD Starter

A starter template for building CRUD (Create, Read, Update, Delete) applications using Spring Boot and Spring MVC. This project provides a clean, modular foundation for rapid development of web applications with a focus on best practices and maintainability.

## Features
- Spring Boot 3.x
- Spring MVC architecture
- CRUD operations (Create, Read, Update, Delete)
- Thymeleaf templating engine (if included)
- H2 in-memory database (default, easily switchable)
- RESTful endpoints
- Modular, clean code structure

## Getting Started

### Prerequisites
- Java 17 or later
- Maven 3.8+

### Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/spring-boot-mvc-crud-starter.git
   cd spring-boot-mvc-crud-starter
   ```
2. **Build the project:**
   ```bash
   mvn clean install
   ```
3. **Run the application:**
   ```bash
   mvn spring-boot:run
   ```
4. **Access the app:**
   - Visit [http://localhost:8080](http://localhost:8080) in your browser.

## Project Structure
```
├── src/main/java/com/example/crud
│   ├── controller
│   ├── model
│   ├── repository
│   ├── service
│   └── CrudApplication.java
├── src/main/resources
│   ├── application.properties
│   └── templates/
└── ...
```

## Usage
- Modify the model, repository, service, and controller packages to fit your domain.
- Update `application.properties` for your database or environment needs.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. 