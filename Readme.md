# E-commerce Checkout Test Automation

## Overview
This project is a Selenium-based test automation script for testing the checkout process of an e-commerce website (https://www.saucedemo.com/). The test script automates various steps including login, navigating the inventory, adding products to the cart, and completing the checkout process.

## Technologies Used
- **Selenium WebDriver** (for web automation)
- **Java** (programming language)
- **TestNG** (test framework)
- **ChromeDriver** (for browser automation)

## Prerequisites
Before running the test script, ensure you have the following installed:
- Java 
- Chrome Browser
- ChromeDriver 
- IDE (Eclipse, IntelliJ IDEA, or any Java-supported IDE)

## Project Setup
1. Clone or download the repository.
2. Open the project in your preferred IDE.
3. Download and set up ChromeDriver:
   - Place it in the system path or set its location in the code.

## Test Scenarios
The script covers the following test scenarios:

1. **Login to the website**
2. **Navigate to inventory page**
3. **Select a product and add it to the cart**
4. **Open cart and verify product**
5. **Proceed to checkout**
6. **Fill in checkout details**
7. **Confirm order**
8. **Return to Home page**
9. **Verify Broken Links**

## Expected Output
- The script will perform the checkout process step-by-step.
- Console logs will display the status of each test case (e.g., login success, product added to cart, order confirmed, etc.).
- A TestNG report will be generated to show the pass/fail status of each test case.

## Tear Down
After execution, the browser will automatically close using the `@AfterClass` method to clean up resources.
