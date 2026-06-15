# JPMC Midas Core - Forage Virtual Experience

## Overview

This project was completed as part of the JPMC Software Engineering Virtual Experience on Forage.

The project demonstrates backend development using Spring Boot, Apache Kafka, H2 Database, JPA, and REST APIs.

## Features

* Kafka Consumer Integration
* H2 Database Integration
* Transaction Validation
* User Balance Management
* Incentive API Integration
* REST API for Balance Query

## Technologies Used

* Java 17
* Spring Boot
* Spring Data JPA
* Apache Kafka
* H2 Database
* Maven
* REST API

## Project Structure

```
src/
 ├── main/
 │    ├── java/
 │    └── resources/
 └── test/
      ├── java/
      └── resources/
```

## Tasks Completed

### Task 1

* Implemented project setup and verified output.

### Task 2

* Integrated Kafka consumer to receive transaction messages.

### Task 3

* Added H2 database support and transaction validation.
* Updated sender and recipient balances.
* Stored transaction records.

### Task 4

* Integrated external Incentive API.
* Added incentive amount to recipient balance.
* Stored incentive information.

### Task 5

* Implemented `/balance` REST endpoint.
* Returned user balance as JSON.
* Configured application to run on port `33400`.

## How to Run

1. Clone the repository
2. Open in IntelliJ IDEA
3. Run:

```
./mvnw spring-boot:run
```

or execute:

```
./mvnw test
```

## Learning Outcomes

* Spring Boot fundamentals
* Kafka messaging
* REST API development
* Database integration with JPA
* Entity relationships
* Maven project management

## Author

Aafrin Zanofiya Fathima

