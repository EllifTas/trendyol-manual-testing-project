# Test Case: Login Attempt with SQL Injection Pattern

## Test Case ID
TC_LOGIN_008

## Objective
To verify that the login form is not vulnerable to basic SQL injection attempts and that the system handles malicious input safely.

## Preconditions
- User is on the login page.

## Test Data
Email: ' OR '1'='1  
Password: ' OR '1'='1

## Test Steps
1. Open the Trendyol login page.
2. Enter the string `' OR '1'='1` into the email field.
3. Enter the string `' OR '1'='1` into the password field.
4. Click the "Login" button.
5. Observe the system response.

## Expected Result
- Login should not be successful.
- The system should not crash or display any SQL/database error messages.
- A generic error such as “Invalid email or password” should be displayed.
- The user should remain on the login page.

## Status
Not Executed
