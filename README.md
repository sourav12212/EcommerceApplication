# <h1 align="center"> E-commerce API Application </h1>
___
<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-4.0-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.1.4-brightgreen.svg" />
</a>
<a href="License url" >
        <img alt="BSD Clause 3" src="https://img.shields.io/badge/License-BSD_3--Clause-blue.svg"/>
    </a>
</p>


---

<p align="left">

## Overview

This project, named "E-commerce API Application," is a robust Spring Boot application designed for building and managing an e-commerce platform's backend. It provides a set of RESTful API endpoints that enable various e-commerce operations, such as managing products, handling orders, user authentication, and more. Whether you're building a small online store or a large-scale e-commerce platform, this application serves as a solid foundation for your backend needs.

## Technologies Used

- **Framework:** Spring Boot
- **Language:** Java
- **Build Tool:** Maven

  ## Dependencies

The E-commerce API Application uses the following dependencies:

- **Spring Boot Starter Data JPA**
  - **Description:** Provides support for JPA (Java Persistence API) and simplifies database access using Spring Data repositories.
  - **Maven Dependency:**
    ```xml
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-data-jpa</artifactId>
    </dependency>
    ```

- **Spring Boot Starter Web**
  - **Description:** Provides support for building web applications, including RESTful APIs.
  - **Maven Dependency:**
    ```xml
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    ```

- **MySQL Connector/J (Runtime Dependency)**
  - **Description:** The MySQL JDBC driver for connecting to MySQL databases.
  - **Maven Dependency:**
    ```xml
    <dependency>
        <groupId>com.mysql</groupId>
        <artifactId>mysql-connector-j</artifactId>
        <scope>runtime</scope>
    </dependency>
    ```

- **Project Lombok (Optional)**
  - **Description:** A library that simplifies Java code by reducing boilerplate code, such as getters and setters.
  - **Maven Dependency:**
    ```xml
    <dependency>
        <groupId>org.projectlombok</groupId>
        <artifactId>lombok</artifactId>
        <optional>true</optional>
    </dependency>
    ```

- **Spring Boot Starter Test (For Testing)**
  - **Description:** Provides support for testing Spring Boot applications.
  - **Maven Dependency (Test Scope):**
    ```xml
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>
    ```

- **Springdoc OpenAPI (Swagger UI)**
  - **Description:** Adds Swagger UI for documenting and testing your API endpoints.
  - **Maven Dependency:**
    ```xml
    <dependency>
        <groupId>org.springdoc</groupId>
        <artifactId>springdoc-openapi-starter-webmvc-ui</artifactId>
        <version>2.1.0</version>
    </dependency>
    ```

- **Spring Boot Starter Validation**
  - **Description:** Includes validation support for request data binding and response data rendering.
  - **Maven Dependency:**
    ```xml
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-validation</artifactId>
    </dependency>
    ```

    ## Data Structures Used

The project utilizes the following data structures:

#### User Class

The `User` class defines the structure for user data and includes fields such as `userId`, `username`, `email`, `password`.

#### Product Class

The `Product` class defines the structure for product data and includes fields such as `productId`, `productName`, `price`, `quantity`, `description`.

#### Orders Class

The `Order` class defines the structure for order data and includes fields such as `orderId`, `productQuantity`.

#### ArrayList Usage

ArrayLists can be used to represent lists of items in your application. For example, you can use an ArrayList to represent a list of order items in an order.

## Project Summary

The E-commerce API Application is a comprehensive Spring Boot application designed to serve as the backend for an e-commerce platform. It offers a wide range of RESTful API endpoints for user management, product management, order processing, and more.

#### Key Technologies Used

- **Framework:** Spring Boot
- **Language:** Java
- **Build Tool:** Maven

### Data Flow

#### Controller

The Controller layer handles incoming HTTP requests and routes them to the appropriate services. It defines API endpoints for various operations related to users, products, orders, and more.

#### Services

The Services layer implements core business logic, data processing, and interaction with the data repository. It handles data validations, CRUD operations, order processing, authentication, and more.

#### Repository

The Repository layer manages data access to the underlying database. It handles database operations for users, products, and orders.

### Database Design

The project's database design includes tables for users, products, orders, and Address, each with specific fields. This design ensures data integrity and organized storage.

The project utilizes data structures such as the `User`, `Product`, `Orders`, and `Address` classes to represent and manage user, product, and order data.

### Key Features

- RESTful API endpoints for user management, product management, and order processing.
- Secure user authentication and authorization with Spring Security.
- Comprehensive data validation for user registration and product management.
- Flexible order creation and management with associated order items.
- Clean code separation with a layered architecture (Controller, Services, Repository).

The E-commerce API Application serves as a robust foundation for building and managing the backend of your e-commerce platform. Whether you're developing a small online store or a large-scale marketplace, this application provides the essential functionality you need to get started.

<!-- License -->
## License

This project is licensed under the [BSD 3-Clause License](LICENSE).

<!-- Acknowledgments -->
## Acknowledgments

Thank you to the Spring Boot and Java communities for providing excellent tools and resources.

<!-- Contact -->
## Contact

For questions or feedback, please contact [Sourav Das](sourav12212@gmail.com).
