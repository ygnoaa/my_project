# Gradle Java Example

A simple Java project managed with Gradle. This project includes the Gradle Wrapper (`gradlew`) to ensure consistent builds across different environments without requiring a pre-installed Gradle distribution.

## Prerequisites

- **Java Development Kit (JDK)**: Version 8 or higher is recommended.
- Ensure your `JAVA_HOME` environment variable is set to your JDK installation path.

## Getting Started

Clone the repository and navigate into the project directory:

```bash
cd gradle-java-example
```

## Build and Run Instructions

### On Windows
Use the provided `gradlew.bat` script:

* **Build the project:**
  ```cmd
  gradlew.bat build
  ```
* **Run the application:**
  ```cmd
  gradlew.bat run
  ```
* **Clean the build directory:**
  ```cmd
  gradlew.bat clean
  ```

## Project Structure
- `gradlew.bat`: Gradle wrapper script for Windows.
- `gradle/`: Contains the Gradle wrapper JAR and properties files.