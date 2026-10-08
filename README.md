# E_Commerce_Automation_Testing

# Selenium SauceDemo Automation Assignment

This project demonstrates Selenium WebDriver automation using Java on the SauceDemo website.

## Tech Stack

- Java
- Selenium WebDriver
- Maven
- Chrome Browser
- IntelliJ IDEA / Eclipse

## Automation Flow

1. Launch SauceDemo website
2. Login using standard user credentials
3. Open the product sorting dropdown
4. Display all available sorting options
5. Select "Price (low to high)"
6. Verify the selected sorting option
7. Identify the cheapest product
8. Add the cheapest product to the cart
9. Navigate to checkout
10. Enter customer information
11. Verify the selected product
12. Display product price, tax and total
13. Complete the order
14. Close the browser

## Website

https://www.saucedemo.com/

## Key Selenium Concepts Used

- WebDriver
- ChromeDriver
- Locators
- `findElement()`
- `findElements()`
- `sendKeys()`
- `click()`
- `Select`
- `getOptions()`
- `getFirstSelectedOption()`
- Dropdown handling
- Dynamic product identification
- String manipulation
- Price comparison
- Basic validation

## Test Credentials

Username: `standard_user`

Password: `secret_sauce`

## Expected Result

The automation should:

- Successfully login
- Select "Price (low to high)"
- Identify the cheapest product
- Add it to the cart
- Verify the product during checkout
- Complete the order successfully


