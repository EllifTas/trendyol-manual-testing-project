# Test Case: Checkout with Invalid CVV Code

## Test Case ID
TC_CHECKOUT_005

## Objective
To verify that the system rejects payment when an invalid CVV code is entered.

## Preconditions
- User is logged in.
- Cart contains at least one product.
- Checkout page is accessible.

## Test Data
Shipping address: All valid.  

Payment details:
- Card Number: 4111 1111 1111 1111 (test card)
- Expiry Date: 12/28
- CVV: 9 (too short) or 9999 (too long)
- Cardholder Name: Test User

## Test Steps
1. Log in with a valid user account.
2. Add at least one product to the cart.
3. Navigate to the checkout page.
4. Fill in shipping fields with valid data.
5. Enter a valid card number and expiry date.
6. Enter an invalid CVV (wrong length or invalid format).
7. Click "Pay" or "Place Order".
8. Observe the payment result.

## Expected Result
- Payment should be declined.
- A clear error message such as "Invalid CVV" or "Please check your security code" should be displayed.
- No order should be created.

## Status
Not Executed
