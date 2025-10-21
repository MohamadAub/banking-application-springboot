# Banking Application using Java 8, Spring Boot & H2 DB
A RESTful API built using Spring Boot, Spring Security, and H2 Database, simulating core banking operations like customer management, account creation, deposits, withdrawals, and internal transfers.

Features

✅ CRUD operations for customers and accounts

✅ Support for deposits and withdrawals

✅ Internal fund transfers between accounts

✅ In-memory H2 Database for easy testing

✅ Integrated Swagger UI for API documentation

✅ Built with secure Spring Security authentication

Tech Stack

- Java 8

- Spring Boot

- Spring Security

- Spring Data JPA

- H2 Database

- Lombok

- Swagger (Springfox)

- Maven

spring-boot-starter-actuator
spring-boot-starter-data-jpa
spring-boot-starter-security
spring-boot-starter-web
spring-boot-devtools
com.h2database:h2
org.projectlombok:lombok
io.springfox:springfox-swagger2
io.springfox:springfox-swagger-ui
spring-boot-starter-test
spring-security-test

Getting Started
1️⃣ Clone the repository
git clone https://github.com/MohamadAub/banking-application-springboot.git
2️⃣ Open the project in your IDE

Make sure Lombok is installed and enabled in your IDE
➡ [Lombok Setup Guide](https://projectlombok.org/setup/eclipse)

3️⃣ Run the project

mvn clean install
mvn spring-boot:run

Access the Application
➤ Swagger UI (API Docs)

http://localhost:8989/bank-api/swagger-ui.html

➤ H2 Database Console

http://localhost:8989/bank-api/h2-console

Use this JDBC URL:
jdbc:h2:mem:testdb
Testing the API

You can test all endpoints using Swagger UI or Postman.
Example request files are located in /src/test/resources.

License

This project is licensed under the MIT License — you are free to use and modify it.
