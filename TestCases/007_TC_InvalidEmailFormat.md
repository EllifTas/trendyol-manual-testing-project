# Test Case: Login Attempt with Invalid Email Format

## Test Case ID
TC_LOGIN_007

## Objective
To verify that the system validates the email format and prevents login when the email does not follow a valid format.

## Preconditions
- User is on the login page.

## Test Data
Email: testexample.com   (no "@" symbol)
Password: Test1234!

## Test Steps
1. Open the Trendyol login page.
2. Enter an invalid email format (e.g. "testexample.com") into the email field.
3. Enter a valid password into the password field.
4. Click the "Login" button.
5. Observe the system response.

## Expected Result
- Login should not be allowed.
- The system should display a validation message for the email field, such as:
  "Please enter a valid email address."
- The user should remain on the login page.

## Status
Not Executed
