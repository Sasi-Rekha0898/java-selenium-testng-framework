# Java Selenium TestNG Automation Framework

## Overview

This project is a Selenium Automation Framework developed using Java, Selenium WebDriver, and TestNG.

The framework follows the Page Object Model (POM) design pattern and supports reusable utilities, reporting, and CI/CD integration.

---

## Tech Stack

* Java
* Selenium WebDriver
* TestNG
* Maven
* Allure Reports
* GitHub Actions

---

## Framework Features

* UI Automation Testing
* Page Object Model Design
* Reusable Utility Classes
* Allure Reporting
* Screenshot Capture on Failure
* Maven Build Management
* CI/CD Integration using GitHub Actions

---

## Project Structure

```bash
src/
│
├── main/java
├── test/java
├── test/resources
│
├── pom.xml
└── testng.xml
```

---

## Installation

Clone repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
mvn clean install
```

---

## Run Tests

```bash
mvn test
```

---

## Generate Allure Report

```bash
allure serve allure-results
```

---

## CI/CD Integration

GitHub Actions is integrated for automated test execution on code push.

---

## Author

Sasi Rekha
