# Test Case: Multiple Failed Login Attempts in a Short Time

## Test Case ID
TC_LOGIN_009

## Objective
To verify that the system handles multiple consecutive failed login attempts safely and does not crash or behave unexpectedly.

## Preconditions
- User is on the login page.

## Test Data
Email: testuser@example.com  
Password: WrongPassword123!

## Test Steps
1. Open the Trendyol login page.
2. Enter a valid email and an invalid password.
3. Click the "Login" button.
4. Repeat steps 2–3 five times within a short period (e.g. 1–2 minutes).
5. Observe the system response after each attempt.

## Expected Result
- Login should fail on each attempt.
- The system should not crash or become unresponsive.
- The system may show a generic warning such as:
  "Too many failed attempts. Please try again later."
  (if such a security control exists).
- The user should remain on the login page.

## Status
Not Executed
