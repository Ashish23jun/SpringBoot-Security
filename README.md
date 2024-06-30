# Spring Security with FilterChain and JWT Tokens
Welcome to the Spring Security with FilterChain and JWT Tokens project! This repository contains a sample Spring Boot application that demonstrates how to implement security using JWT tokens and custom filter chains.
## Table of Content
#### Introduction
#### Features
#### Getting Started
#### Prerequisites
#### Installation
#### Configuration
#### Running the Application
## Introduction
This project showcases how to secure a Spring Boot application using JSON Web Tokens (JWT) and custom filter chains. JWT is a compact, URL-safe means of representing claims to be transferred between two parties. Using JWT in a Spring Boot application allows for stateless authentication and authorization.

## Features
JWT-based authentication and authorization,
Custom filter chain for request processing
Role-based access control, 
Secure endpoints using annotations,
In-memory user details service for simplicity,
RESTful APIs for user login and access


## Prerequisites
Java 17 or higher,
Maven or Gradle and
An IDE (IntelliJ, Eclipse, etc.)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
git clone https://github.com/your-username/spring-security-jwt.git
cd spring-security-jwt

```
```bash
mvn clean install
```



## Configuration
```python
Properties

server.port=8080
jwt.secret=your_jwt_secret_key
jwt.expiration=86400000
```

## Running the Application
```python
bash

mvn spring-boot:run
```
## License

[MIT](https://choosealicense.com/licenses/mit/)
