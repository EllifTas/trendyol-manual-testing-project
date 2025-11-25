# Test Case: Add to Cart as Guest User

## Test Case ID
TC_CART_007

## Objective
To verify that a guest user (not logged in) can add items to the cart and that the behavior is consistent.

## Preconditions
- User is NOT logged in.
- User can access product detail pages.

## Test Steps
1. Ensure the user is logged out.
2. Open the product detail page of an in-stock product.
3. Click "Add to Cart".
4. Open the cart page.
5. Observe cart contents.

## Expected Result
- Guest user should be able to add the product to the cart.
- The product should appear in the cart with correct details.
- If the application requires login at checkout, this should happen later in the checkout flow, not at add-to-cart.

## Status
Not Executed
