# Software-Testing-Project
Software Testing Project for DEPI

🏦 Parabank Testing Project
This project is focused on testing the Parabank online banking demo application using:

✅ Postman for REST API testing

🤖 Selenium for UI automation testing

🧪 Manual Testing with bug reporting

📌 Project Goals
Validate functionality of user registration and login via APIs and UI

Identify functional bugs in the Parabank web application

Practice automated test case creation and execution

Document and report discovered bugs in a structured format

🧪 Testing Tools
Tool	Purpose
Postman	API requests & testing
Selenium	UI automation tests
Browser	Manual testing

🚀 Getting Started
✅ Prerequisites
Postman

Python (if you're using Selenium in Python)

Selenium + Chrome WebDriver

Git

📬 API Testing (Postman)
Tested endpoints:

POST /register.htm → User Registration

POST /login.htm → User Login

Used x-www-form-urlencoded body format

Tested success & failure cases (e.g., missing fields, invalid data)

Postman collection is included in the repo under /postman/Parabank.postman_collection.json

🤖 Selenium UI Tests
Automated UI test cases using Selenium:

Register a new user

Log in with valid credentials

Attempt login with invalid credentials

Script location: /selenium_tests/

📝 Manual Testing
Performed exploratory and scenario-based testing

Checked:

Form validation

Error messages

Navigation flows

Tested browsers: Chrome, Firefox

🐞 Bug Reports
All discovered bugs are listed in /bug_reports/bugs.md

Each report includes:

Bug ID

Summary

Steps to Reproduce

Expected vs Actual Behavior

Severity

Screenshot (if applicable)

