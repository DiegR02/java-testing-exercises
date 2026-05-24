# java-testing-exercises

A hands-on collection of Java testing exercises designed to build familiarity with unit testing concepts, assertions, and test-driven development (TDD) practices.

---

## Overview

This repository serves as a personal learning sandbox for practising software testing in Java. Each exercise targets a specific testing concept or technique, making it easy to revisit individual topics as skills develop.

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Java |
| Testing framework | JUnit (4 / 5) |
| Build tool | Maven or Gradle (confirm in project root) |
| IDE target | IntelliJ IDEA / Eclipse / VS Code |

## Repository Structure

```
java-testing-exercises/
├── src/
│   ├── main/java/        # Source classes under test
│   └── test/java/        # Test cases and exercises
├── pom.xml / build.gradle
└── README.md
```

> Adjust the tree above to match the actual layout once reviewed.

## Getting Started

### Prerequisites

- Java 11 or later
- Maven 3.8+ **or** Gradle 7+

### Clone the repository

```bash
git clone https://github.com/DiegR02/java-testing-exercises.git
cd java-testing-exercises
```

### Run all tests

```bash
# Maven
mvn test

# Gradle
gradle test
```

> Confirm the exact build tool and commands by inspecting the project root before running.

## Usage

Browse the `src/test/java` directory to find individual exercise files. Each file focuses on a specific testing topic such as:

- Basic assertions and matchers
- Exception testing
- Parameterised tests
- Mocking with Mockito (if included)
- Test lifecycle annotations (`@BeforeEach`, `@AfterEach`, etc.)

Open an exercise, read the inline comments, and implement or extend the test cases to complete the exercise.

## Learning Goals

- Understand the structure of a well-written unit test
- Apply the Arrange–Act–Assert (AAA) pattern consistently
- Practise test-driven development by writing tests before implementation
- Build confidence with JUnit 5 and common testing utilities

## Project Status

| Field | Value |
|---|---|
| Status | Active learning |
| Category | Learning project |
| Priority | Low |
| Portfolio role | Practice / skill demonstration |

This is a personal practice repository, not production software. Code quality and coverage will improve incrementally as exercises are completed.

## Contributing

This repository is primarily for personal learning. Suggestions and corrections are welcome via issues.

## License

See the [LICENSE](LICENSE) file for details.
