# Bug Report: Invalid Login Error Message Not Displayed

## Bug ID
BR_001

## Title
No error message is shown when the user attempts to log in with invalid credentials.

## Environment
- Web: Chrome 120+
- OS: macOS / Windows (reproducible on both)
- App Version: N/A (Testing Trendyol web flow simulation)

## Severity
Major

## Priority
High

## Precondition
User is on the login page.

## Steps to Reproduce
1. Navigate to the login page.
2. Enter an invalid email: `wrongemail@example.com`
3. Enter an invalid password: `WrongPass123!`
4. Click the “Login” button.
5. Observe the system response.

## Expected Result
- An error message such as **"Invalid email or password"** should be displayed.
- The user should remain on the login page.

## Actual Result
- No error message is displayed.
- The page reloads without informing the user that the credentials are incorrect.

## Screenshot / Attachment
(N/A)

## Notes
This issue affects usability and can confuse users because there is no feedback after a failed login attempt.
