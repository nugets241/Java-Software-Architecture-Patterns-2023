# Software Architecture - Design Patterns

This repository contains several projects demonstrating the use of various design patterns in Java. Each project is a Maven project and can be built and run independently.

## Projects

1. Java Adapter Design Pattern 2023
2. Java Identity Management System 2023
3. Java Observer Design Pattern 2023
4. Java Strategy Design Pattern 2023

## Prerequisites

- Java 11
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

Replace <artifactId> and <version> with the artifact ID and version specified in the pom.xml file of the project.

## Running Tests
To run the tests for a project, navigate to the project directory in your terminal and run the following command:

```sh
mvn test
```
