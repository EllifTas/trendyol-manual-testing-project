# Test Case: Login Attempt with Empty Fields

## Test Case ID
TC_LOGIN_004

## Objective
To verify that the system prevents login when required fields are left empty and displays appropriate validation messages.

## Preconditions
- User is on the login page.

## Test Data
Email: (empty)
Password: (empty)

## Test Steps
1. Open the Trendyol login page.
2. Leave the email field empty.
3. Leave the password field empty.
4. Click the "Login" button.
5. Observe the system response.

## Expected Result
- Login should not be allowed.
- The system should display validation messages for the required fields, such as:
  - "Email is required."
  - "Password is required."
- The user should remain on the login page.

## Status
Not Executed
