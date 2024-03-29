# HF Design Patterns - Adapter 2023

This is a starter project for the Adapter Design Pattern. It's a Java Maven project that demonstrates the use of the Adapter Design Pattern through a simple example involving Ducks and Turkeys.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Java 11
- Maven

### Installing

1. Clone the repository:
git clone ...URL...
cd ...THE-DIR...

2. Build the project:
mvn clean install # or package

## Running the Project

You can run the application in two ways:

1. Run the main() in App.java (defined in the manifest file of the jar):
java -jar target/adapter-1.0-SNAPSHOT.jar

2. Run the main() in some other file:
java -cp target/adapter-1.0-SNAPSHOT.jar org.sad22.adapter.App

This will run the main method in the App class.

## Running the Tests
To run the tests, use the following command:

mvn test
