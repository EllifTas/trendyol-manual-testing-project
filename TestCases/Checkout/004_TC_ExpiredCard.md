# Test Case: Checkout with Expired Card

## Test Case ID
TC_CHECKOUT_004

## Objective
To verify that the system rejects payment when an expired card is used.

## Preconditions
- User is logged in.
- Cart contains at least one product.
- Checkout page is accessible.

## Test Data
Shipping address: All valid.  

Payment details:
- Card Number: 4111 1111 1111 1111 (test card)
- Expiry Date: 01/23 (expired)
- CVV: 123
- Cardholder Name: Test User

## Test Steps
1. Log in with a valid user account.
2. Add at least one product to the cart.
3. Navigate to the checkout page.
4. Fill in all shipping fields with valid data.
5. Enter a card with an expiry date in the past.
6. Enter valid CVV.
7. Click "Pay" or "Place Order".
8. Observe the payment result.

## Expected Result
- Payment should be declined.
- An error message such as "Card has expired" should be shown.
- No order should be created.
- User should remain on the checkout page.

## Status
Not Executed
