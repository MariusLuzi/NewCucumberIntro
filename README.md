# NewCucumberIntro 🥒

A hands-on introduction to Behavior-Driven Development (BDD) using Cucumber with Java and Selenium WebDriver.

## 📖 About This Project

This repository serves as a practical starter project for learning Behavior-Driven Development (BDD) with Cucumber-JVM. It demonstrates the fundamental concepts of BDD, including feature files, step definitions, and test automation with Selenium WebDriver.

## 🚀 Technologies Used

- **Cucumber JVM** - BDD framework
- **Selenium WebDriver** - Browser automation
- **Java** - Programming language
- **Maven** - Dependency management
- **JUnit** - Test runner

## 📁 Project Structure
NewCucumberIntro/
├── src/
│ └── test/
│ ├── java/
│ │ └── stepdefinitions/
│ │ └── ExampleSteps.java
│ └── resources/
│ └── features/
│ └── example.feature
├── pom.xml
└── README.md


## 🛠️ Setup Instructions

### Prerequisites
- Java JDK 8 or higher
- Maven 3.6+
- Chrome/Firefox browser

### Installation
1. Clone this repository:
git clone https://github.com/MariusLuzi/NewCucumberIntro.git
Navigate to the project directory:

bash
cd NewCucumberIntro
Run the tests:

bash
mvn test
🧪 Running Tests
Execute all Cucumber tests:

bash
mvn test
Run with specific tags:

bash
mvn test -Dcucumber.filter.tags="@smoke"
📝 Features
Basic BDD concepts with Gherkin syntax

Step definitions implementation

Selenium WebDriver integration

Page Object Model examples

Maven project configuration

🎯 Learning Objectives
Understand BDD principles and Gherkin language

Create feature files with scenarios

Implement step definitions in Java

Integrate Cucumber with Selenium WebDriver

Configure Maven for test automation

Generate test reports

🤝 Contributing
This is a learning project. Feel free to fork and experiment with different Cucumber features and patterns!

📄 License
This project is open source and available under the MIT License.
