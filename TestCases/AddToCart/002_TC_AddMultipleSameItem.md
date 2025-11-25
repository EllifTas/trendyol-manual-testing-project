# Test Case: Add the Same Product to Cart Multiple Times

## Test Case ID
TC_CART_002

## Objective
To verify that adding the same product multiple times updates the quantity correctly in the cart.

## Preconditions
- User is on a valid product detail page.
- The product is in stock.

## Test Data
Product: Any in-stock product

## Test Steps
1. Open the product detail page of an in-stock product.
2. Click the "Add to Cart" button.
3. Click the "Add to Cart" button again for the same product.
4. Open the cart page.
5. Observe the quantity and total price.

## Expected Result
- The product should appear only once in the cart.
- Quantity should be updated to 2.
- Total price should be calculated as `unit price x 2`.

## Status
Not Executed
