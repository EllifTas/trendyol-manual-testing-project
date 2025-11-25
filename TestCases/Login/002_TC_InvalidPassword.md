# Test Case: Login Attempt with Invalid Password

## Test Case ID
TC_LOGIN_002

## Objective
To verify that the system prevents login when a valid email is entered with an invalid password and displays the correct error message.

## Preconditions
- User has an active account.
- User is on the login page.

## Test Data
Email: testuser@example.com
Password: WrongPassword123!

## Test Steps
1. Open the Trendyol login page.
2. Enter a valid email into the email field.
3. Enter an invalid password into the password field.
4. Click the "Login" button.
5. Observe the system response.

## Expected Result
- Login should fail.
- The system should display an error message such as:
  “Invalid email or password.”
- The user should remain on the login page.

## Status
Not Executed
