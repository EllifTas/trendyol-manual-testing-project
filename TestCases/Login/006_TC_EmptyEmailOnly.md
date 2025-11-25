 # Test Case: Login Attempt with Empty Email

## Test Case ID
TC_LOGIN_006

## Objective
To verify that the system prevents login when the email field is left empty while the password field contains a valid password.

## Preconditions
- User is on the login page.

## Test Data
Email: (empty)  
Password: Test1234!

## Test Steps
1. Open the Trendyol login page.
2. Leave the email field empty.
3. Enter a valid password into the password field.
4. Click the "Login" button.
5. Observe the system response.

## Expected Result
- Login should not be allowed.
- The system should display a validation message for the email field, such as:
  "Email is required."
- No error should appear for the password field.
- The user should remain on the login page.

## Status
Not Executed
