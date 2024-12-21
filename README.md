# Java Software Architecture Patterns 2024

This repository contains several projects demonstrating the use of various design patterns in Java. Each project is a Maven project and can be built and run independently.

## Projects

1. [Java Adapter Design Pattern 2023](Java-Adapter-Design-Pattern-2023)
2. [Java Identity Management System 2023](Java-IdentityManagement-2023)
3. [Java Observer Design Pattern 2023](Java-Observer-Design-Pattern-2023)
4. [Java Strategy Design Pattern 2023](Java-Strategy-Design-Pattern-2023)

## Prerequisites

- Java 11 or higher
- Maven

## Building and Running a Project

Navigate to the project directory in your terminal and run the following command to build the project:

```sh
mvn clean install
```

This will compile the Java classes, run any tests, and package the application into a JAR file.

After building the project, you can run the application with the following command:

```sh
java -jar target/<artifactId>-<version>.jar
```

Replace `<artifactId>` and `<version>` with the artifact ID and version specified in the `pom.xml` file of the project.

## Running Tests

To run the tests for a project, navigate to the project directory in your terminal and run the following command:

```sh
mvn test
```

## Project Descriptions

### Java Adapter Design Pattern 2023

This project demonstrates the Adapter Design Pattern through a simple example involving Ducks and Turkeys.

### Java Identity Management System 2023

This project demonstrates the use of the Adapter Design Pattern in the context of an Identity Management System. It includes classes such as Contact, IDMAdapter, ContactAdapter, ContactsService, and ContactAttributeStrategy.

### Java Observer Design Pattern 2023

This project demonstrates the Observer Design Pattern using a weather station example. It includes classes such as WeatherData, CurrentConditionsDisplay, and WeatherStation.

### Java Strategy Design Pattern 2023

This project demonstrates the Strategy Design Pattern using a Duck example. It includes classes such as Duck, MallardDuck, RedheadDuck, RubberDuck, and ModelDuck.

## Acknowledgments

Inspired by the Head First Design Patterns book.
Special thanks to the open-source community for providing valuable resources and tools.