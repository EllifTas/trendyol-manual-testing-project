# Test Case: Add Out-of-Stock Product to Cart

## Test Case ID
TC_CART_006

## Objective
To verify that out-of-stock products cannot be added to the cart.

## Preconditions
- User is on the product detail page of an out-of-stock product (if available), or
- Product shows "Out of stock" label.

## Test Steps
1. Open the product detail page of an out-of-stock product.
2. Observe the "Add to Cart" button.
3. Attempt to click "Add to Cart" (if enabled).
4. Open the cart page (if action is allowed) and observe contents.

## Expected Result
- "Add to Cart" button should be disabled **or**
- Clicking it should not add the product to the cart.
- A clear message such as "This product is out of stock" should be displayed.
- The product should not appear in the cart.

## Status
Not Executed
