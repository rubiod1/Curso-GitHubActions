# My Java Application

This project is a simple Java application that demonstrates the basic structure of a Java project using Maven.

## Project Structure

```
my-java-app
├── src
│   └── Main.java
├── .vscode
│   └── launch.json
├── pom.xml
└── README.md
```

## Prerequisites

- Java Development Kit (JDK) installed on your machine.
- Maven installed on your machine.
- A code editor such as Visual Studio Code.

## Building the Application

To build the application, navigate to the project directory and run the following command:

```
mvn clean install
```

## Running the Application

After building the application, you can run it using the following command:

```
mvn exec:java -Dexec.mainClass="Main"
```

## Debugging the Application

To debug the application, open the project in Visual Studio Code and use the provided launch configuration in the `.vscode/launch.json` file. Set breakpoints in your code and start debugging.

## License

This project is licensed under the MIT License.