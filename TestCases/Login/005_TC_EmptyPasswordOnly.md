# Test Case: Login Attempt with Empty Password

## Test Case ID
TC_LOGIN_005

## Objective
To verify that the system prevents login when the password field is left empty while the email field contains a valid email address.

## Preconditions
- User is on the login page.

## Test Data
Email: testuser@example.com  
Password: (empty)

## Test Steps
1. Open the Trendyol login page.
2. Enter a valid email into the email field.
3. Leave the password field empty.
4. Click the "Login" button.
5. Observe the system response.

## Expected Result
- Login should not be allowed.
- The system should display a validation message for the password field, such as:
  "Password is required."
- No error should appear for the email field.
- The user should remain on the login page.

## Status
Not Executed
