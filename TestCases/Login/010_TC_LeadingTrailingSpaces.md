# Test Case: Login with Leading and Trailing Spaces in Credentials

## Test Case ID
TC_LOGIN_010

## Objective
To verify that the system handles leading and trailing spaces in the email and password fields correctly and still allows login with valid credentials.

## Preconditions
- User has an active account.
- User is on the login page.

## Test Data
Email: "  testuser@example.com  "   (with spaces before and after)
Password: "  Test1234!  "           (with spaces before and after)

## Test Steps
1. Open the Trendyol login page.
2. Enter the email value with leading and trailing spaces into the email field.
3. Enter the password value with leading and trailing spaces into the password field.
4. Click the "Login" button.
5. Observe the system response.

## Expected Result
- The system should trim unnecessary spaces and treat the credentials as valid.
- Login should be successful.
- The user should be redirected to the homepage or user dashboard.

## Status
Not Executed
