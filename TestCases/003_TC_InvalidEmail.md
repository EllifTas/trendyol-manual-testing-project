# Test Case: Login Attempt with Invalid Email

## Test Case ID
TC_LOGIN_003

## Objective
To verify that the system prevents login when an invalid email is entered and displays the correct error message.

## Preconditions
- User is on the login page.

## Test Data
Email: invalidemail@example  
Password: Test1234!

## Test Steps
1. Open the Trendyol login page.
2. Enter an invalid email into the email field.
3. Enter a valid password into the password field.
4. Click the "Login" button.
5. Observe the system response.

## Expected Result
- Login should fail.
- The system should display an error message such as:
  "Please enter a valid email."
- The user should remain on the login page.

## Status
Not Executed
