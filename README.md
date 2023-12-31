# Playwright_PageObjectModel

This project while doing a DEMO tutorial on How to create Page Object Model framework in Playwright
This is done on a Node project with JavaScript

### Tools & Technologies
* Node JS
* VS Code
* JavaScript

### Tutorial Steps - Playwright Page Object Model Project

* Step 1 - Create a new folder and open in IDE or Editor (like VS Code)
* Step 2 - Initialize a new Node.js project by running **`npm init -y`** to create a package.json file
* Step 3 - Install & Setup Playwright by running **`npm init playwright@latest`**
* Step 4 - Create a demo login test, can use Test Generator to record **`npx playwright codegen`**
* Step 5 - Run tests and check results - **`npx playwright test`**  & **`npx playwright show-report`**
* Step 6 - Create new folder "pages" in your project, this will contain all page objects
* Step 7 - Create a new file and class for each page e.g. login.js and LoginPage
* Step 8 - In the class create element locators & action methods for login page
* Step 9 - In test file, import the page class, create instance of it, & use methods from LoginPage class

