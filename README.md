![GitHub views](https://komarev.com/ghpvc/?username=keryit&repo=microservices_bank_app&color=blue)


# Microservices Bank Application

This repository contains a microservices-based project, demonstrating key concepts of designing and developing distributed systems using Spring Boot. 
This project demonstrates a banking application implemented using a microservices architecture. It provides core functionalities such as customer and account management, supported by additional features like service discovery, centralized configuration, and an API gateway for seamless interaction.

## Table of Contents
1. [Overview](#overview)  
2. [Technologies](#technologies)  
3. [Modules](#modules)  
4. [Getting Started](#getting-started)  
5. [Running the Application](#running-the-application)  
6. [API Documentation](#api-documentation)  

---

## Overview

This project demonstrates:
- Building microservices with Spring Boot.
- Implementing inter-service communication using REST and messaging systems.
- Securing microservices with Spring Security.
- Leveraging cloud-based tools for configuration and service discovery.

  ### Supporting Components

- **API Gateway**: Routes client requests to appropriate microservices.

- **Eureka Server**: Handles service discovery and registration for the microservices.

- **Centralized Configuration**: Manages configuration files for all microservices in one place.




### Key Features
- Decoupled architecture with independently deployable microservices.
- Centralized configuration and service registry.
- Implementation of fault-tolerance mechanisms.
- API gateway for unified request handling.

---

## Technologies Used

- **Backend Framework**: Spring Boot, Spring Cloud

- **Service Communication**: RESTful APIs

- **Service Discovery**: Eureka Server

- **Configuration Management**: Spring Cloud Config

- **Infrastructure**: Docker, Kubernetes (deployment)

- **Messaging**: Kafka (for asynchronous communication)

- **Kubernetes** (for orchestration)

- **Apache Kafka** (for messaging)


## Technologies

- **Java 21+**
- **Spring Boot 3.3.5**:
  - Spring Cloud
  - Spring Security
  - Spring Data JPA
- **Database**:
  - MySQL
- **Messaging**:
  - RabbitMQ
- **Service Discovery**:
  - Eureka Server
- **API Gateway**:
  - Spring Cloud Gateway
- **Build Tool**:
  - Maven

---

## Modules

The project is organized into the following modules:

1. **Service Registry**: Manages service discovery.
2. **API Gateway**: Routes external requests to internal services.
3. **Config Server**: Centralized management of service configurations.
4. **Accounts Service**: Handles account-related operations.
5. **Cards Service**: Cards operations.
6. **Loan Service**: Manages loans transactions.

---

## Getting Started

### Prerequisites
- Install [Java 21](https://www.oracle.com/java/technologies/javase-downloads.html).
- Install [Maven](https://maven.apache.org/install.html).
- Install and configure [MySQL](https://www.mysql.com/).
- Install [RabbitMQ](https://www.rabbitmq.com/download.html).

### Clone Repository
```bash
git clone https://github.com/keryit/microservices_bank_app.git
cd microservices
git checkout bank_app
```

### Configure Database
1. Update `application.yml` files in each service module to include your database credentials.


---

## Running the Application


---

## API Documentation

The API documentation for each service is available under:
http://localhost:8080/swagger-ui/index.html#/


---
