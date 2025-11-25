# Test Case: Cart Persistence After Page Refresh

## Test Case ID
TC_CART_008

## Objective
To verify that items remain in the cart after refreshing the page or navigating back to the site.

## Preconditions
- Cart contains at least one product.

## Test Steps
1. Add a product to the cart (if not already in cart).
2. Open the cart page and confirm the product is displayed.
3. Refresh the browser page.
4. Observe the cart contents.
5. Close the browser tab and reopen the site (optional, if supported).
6. Navigate to the cart page again.

## Expected Result
- After refresh, the same items should remain in the cart.
- If the application supports persistent carts, items should still be present when the site is reopened (for logged-in users or via cookies/session).

## Status
Not Executed
