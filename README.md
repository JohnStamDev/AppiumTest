#Appium Test Automation for SwagLabs

This project is an automated test suite for the Swag Labs Android app, built with Cucumber, Appium, Java, and JUnit. It was developed as part of a technical assessment to demonstrate key testing skills.

## ✅ What’s Included
- Login tests (positive & negative scenarios)
- Cart functionality tests (add, remove, view cart)
- Cucumber BDD with Gherkin scenarios
- Tagged scenarios for flexible execution
- Page Object Model structure
- Logger integration for easy debugging
- Cucumber report generation

## 🔧 Tech Stack
- Java 17
- Appium
- Cucumber
- JUnit
- Android Studio (emulator)
- IntelliJ IDEA

## 🧪 How to Run the Tests
1. Install dependencies (Java 17+, Appium server)
2. Connect your Android emulator
3. Update `app` path in `BaseTest.java` if needed
4. From terminal: `mvn clean test`
5. After tests, open the report: `target/cucumber-html-reports/index.html`

## 📌 Notes
- App used: Swag Labs APK
- Tested on Android emulator (API 33+)


## 🚀 Future Improvements
Some ideas I’d consider for enhancing this test framework:
- Introduce parallel test execution to speed up regression runs.
- Implement page object validation methods to improve clarity and reduce step duplication.
- Integrate with a test management tool (e.g., Xray or Allure for reporting).
- Expand coverage with more edge cases and user flows.

