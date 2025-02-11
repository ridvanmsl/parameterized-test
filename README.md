# Parameterized Test: A Gradle-based Example

This project demonstrates parameterized testing using JUnit Jupiter in a Gradle environment.  It includes a simple `Calculator` class with a division method and a corresponding test suite (`CalculatorTest`) utilizing parameterized tests to verify the division functionality for various inputs.

## Project Structure

The project directory contains the following:

* **`src/main/java`**: Contains the source code for the `Calculator` class.
* **`src/test/java`**: Contains the JUnit test suite (`CalculatorTest.java`) for the `Calculator` class.
* **`build.gradle`**: Gradle build script defining dependencies and tasks.
* **`settings.gradle`**: Gradle settings file.
* **`gradlew` & `gradlew.bat`**: Gradle wrapper scripts for Linux/Unix and Windows, respectively.
* **`.gitattributes`**: Defines text file handling for Git.
* **`gradle-wrapper.properties`**: Specifies the Gradle wrapper version.


## Tech Stack & Dependencies

* **Java:** Programming language
* **Gradle:** Build automation tool (version 7.2)
* **JUnit Jupiter:** Testing framework (version 5.8.2)
    * `junit-jupiter-api`
    * `junit-jupiter-engine`
    * `junit-jupiter-params`


## Installation & Setup

1. **Prerequisites:** Ensure you have Java Development Kit (JDK) installed and configured correctly.  Set the `JAVA_HOME` environment variable accordingly.
2. **Gradle:** Download and install Gradle (version 7.2 or later recommended) or use the Gradle wrapper included in this project.
3. **Clone the repository:** Clone this repository using Git.
4. **Build the project:** Navigate to the project directory and run `./gradlew build` (Linux/Unix) or `gradlew.bat build` (Windows) from the command line. This compiles the code and runs the tests.


## Usage Guide

The core functionality of this project is encapsulated in the `Calculator.java` and `CalculatorTest.java` files.

*   `Calculator.java` provides a basic `divide` function.
*   `CalculatorTest.java` uses JUnit Jupiter's `@ParameterizedTest` and `@CsvSource` to test multiple inputs of the `divide` function against their expected outputs.


To run the tests, execute the following in your terminal:

```bash
./gradlew test  # Linux/Unix
gradlew.bat test # Windows
```


The test results will be displayed in the console.


## Contribution Guidelines

Contributions are welcome! Please follow these guidelines:

1.  Fork the repository.
2.  Create a new branch for your changes.
3.  Commit your changes with clear and concise messages.
4.  Push your branch to your forked repository.
5.  Create a pull request to merge your changes into the main branch.

Please adhere to the project's coding style.


## License

[Specify License here, e.g., MIT License]


## Author Info

Ridvan Musaoglu
[Optional: Add contact details]

