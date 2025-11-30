# Test Case: Checkout with Invalid Card Number

## Test Case ID
TC_CHECKOUT_003

## Objective
To verify that the system rejects payment when an invalid card number is entered and shows a clear error message.

## Preconditions
- User is logged in.
- Cart contains at least one product.
- Checkout page is accessible.

## Test Data
Shipping address: All required fields valid.  

Payment details:
- Card Number: 1234 5678 9999 0000 (invalid)
- Expiry Date: 12/28
- CVV: 123
- Cardholder Name: Test User

## Test Steps
1. Log in with a valid user account.
2. Add at least one product to the cart.
3. Navigate to the checkout page.
4. Fill in all shipping address fields with valid data.
5. Enter an invalid card number into the card number field.
6. Enter valid expiry date and CVV.
7. Click "Pay" or "Place Order".
8. Observe the payment result.

## Expected Result
- Payment should be declined.
- A clear error message such as "Invalid card number" should be displayed.
- No order should be created.
- User should remain on the checkout page and be able to correct the card number.

## Status
Not Executed
