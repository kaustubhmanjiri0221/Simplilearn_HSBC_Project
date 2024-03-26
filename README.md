# Simplilearn_HSBC_Project

HSBC Website Automation Test

Overview
This project automates tests for the HSBC website using Cypress.io, a popular web application testing framework. The tests verify the functionality and behavior of various elements on the HSBC website, ensuring a smooth user experience.

Setup
Prerequisites:

Node.js and npm (or yarn) installed on your system.
A code editor like Visual Studio Code (VS Code).
Instructions:

Clone the Repository: (If applicable)
Bash
git clone <repository-url>
Use code with caution.
Install Dependencies:
Bash
npm install
``` (or `yarn install`)
Use code with caution.
Run the Tests:
Bash
npm run cypress:open  # This command might vary depending on your project setup
Use code with caution.
This opens the Cypress Test Runner in your browser.
Select the Test File: In the Cypress Test Runner, click on the test file (e.g., search_hsbc_spec.js or HSBC_proj.cy.js) to execute the tests.
Test Description
The test suite (HSBC_proj.cy.js or specific test file) contains a test case named CheckText (or a more descriptive name) that focuses on the HSBC security page login flow:

Validate Login Flow: This test navigates to the security page, interacts with elements like username input, help icon, close button, and login button, verifying their functionality at each step.
Test Steps
Visit the HSBC security page (https://www.hsbc.co.in/security/).
Click on the Username Input field.
Type text into the Username field.
Click on the question mark (?) icon for username help.
Verify the username guide content (optional).
Click on the Close button in the help popup.
Click on the Login button. (Note: Functionality testing for login might require additional considerations)
Refer to the Repository:

For further details about the test structure, additional test cases, and best practices, explore the project repository.

Improvements:

Clearer Structure: The information is categorized for better readability.
Concise Steps: The test steps are more focused and actionable.
Optional Verification: Highlighted an optional step for verifying the username guide content.
Login Button Note: Added a note acknowledging potential complexities in testing the login button functionality.
Repository Reference: Encouraged exploring the repository for deeper understanding.
