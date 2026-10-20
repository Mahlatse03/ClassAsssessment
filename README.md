# ClassAsssessment

A small Java/Maven project for browser automation testing and experimentation with Selenium.

## Overview

This project includes:
- a basic Java entry point in `src/main/java/org/example/Main.java`
- a simple browser factory in `src/test/java/utils/BrowserFactory.java`
- Maven configuration for Java 21 builds

## Prerequisites

- Java 21+
- Maven 3.9+
- Chrome, Firefox, or Edge installed locally
- Matching browser drivers available on your system PATH

## Project Structure

```text
ClassAsssessment/
├── pom.xml
├── src/
│   ├── main/java/org/example/Main.java
│   └── test/java/utils/BrowserFactory.java
└── README.md
```

## Commands

Compile the project:

```bash
mvn compile
```

Run the test suite:

```bash
mvn test
```

## Notes

The browser factory supports launching Chrome, Firefox, and Edge and opening the target URL in a maximized browser window.

This project is a lightweight starting point and can be expanded with page objects, test cases, and additional automation workflows.
