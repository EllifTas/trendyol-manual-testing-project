# Test Case: Checkout with Missing Required Shipping Field

## Test Case ID
TC_CHECKOUT_002

## Objective
To verify that the system does not allow checkout when a required shipping field is left empty and that a proper validation message is displayed.

## Preconditions
- User is logged in.
- Cart contains at least one product.
- Checkout page is accessible.

## Test Data
Shipping address with missing field:
- Name: Test User
- Address: (empty)
- City: Istanbul
- Country: Turkey
- Postal Code: 34000

Payment details:
- Valid mock card information (same as TC_CHECKOUT_001)

## Test Steps
1. Log in with a valid user account.
2. Add at least one product to the cart.
3. Go to the cart page and click "Proceed to Checkout".
4. On the checkout page, fill in all shipping fields **except** the Address field (leave it empty).
5. Enter valid payment card details.
6. Click the "Pay" or "Place Order" button.
7. Observe the system response.

## Expected Result
- Checkout should not be completed.
- A validation error should be shown for the empty Address field (e.g. "Address is required").
- No order should be created.
- The user should remain on the checkout page until the error is fixed.

## Status
Not Executed
