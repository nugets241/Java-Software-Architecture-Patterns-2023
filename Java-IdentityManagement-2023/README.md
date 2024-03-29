# Java Identity Management System 2023

This project demonstrates the use of the Adapter Design Pattern in the context of an Identity Management System.

## Project Structure

The project is organized into the following main directories:

- `src/main/java/fi/tamk/sade23/idm`: This directory contains the main Java classes for the project, including the `Contact`, `IDMAdapter`, `ContactAdapter`, `ContactsService`, and `ContactAttributeStrategy` classes.

- `src/test/java/fi/tamk/sade23/idm`: This directory contains the test classes for the project.

## Building the Project

The project uses Maven for dependency management and building. To build the project, navigate to the project directory in your terminal and run the following command:

```sh
mvn clean install
```
This will compile the Java classes, run any tests, and package the application into a JAR file.

## Running the Project

After building the project, you can run the application with the following command:

```sh
java -jar target/idm-2023a-1.0-SNAPSHOT.jar
```
