# Test Case: Update Item Quantity in Cart

## Test Case ID
TC_CART_004

## Objective
To verify that the user can update the quantity of a product in the cart.

## Preconditions
- Cart contains at least one product with quantity = 1.

## Test Data
Initial Quantity: 1  
New Quantity: 3

## Test Steps
1. Open the cart page.
2. Locate a product with quantity set to 1.
3. Change the quantity to 3 using the quantity selector (plus button or dropdown).
4. Observe the updated quantity and total price.

## Expected Result
- Quantity should update from 1 to 3.
- Line item total price should be updated as `unit price x 3`.
- Cart total should be updated accordingly.

## Status
Not Executed
