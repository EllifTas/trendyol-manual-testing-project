# Test Case: Cancel Checkout and Return to Cart

## Test Case ID
TC_CHECKOUT_006

## Objective
To verify that the user can safely cancel the checkout process and return to the cart without creating an order.

## Preconditions
- User is logged in.
- Cart contains at least one product.
- Checkout page is accessible.

## Test Data
Any valid cart contents.

## Test Steps
1. Log in with a valid user account.
2. Add at least one product to the cart.
3. Navigate to the checkout page.
4. Click the "Cancel", "Back to Cart" or similar button/link.
5. Observe the navigation and cart contents.

## Expected Result
- User should be redirected back to the cart page.
- No order should be created.
- Cart should still contain the previously added items.
- No payment attempt should be processed.

## Status
Not Executed
