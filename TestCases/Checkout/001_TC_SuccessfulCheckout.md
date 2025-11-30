# Test Case: Successful Checkout with Valid Payment (Logged-in User)

## Test Case ID
TC_CHECKOUT_001

## Objective
To verify that a logged-in user can successfully complete the checkout flow using valid shipping information and valid payment details (mock payment).

## Preconditions
- User is logged in.
- Cart contains at least one in-stock product.
- Checkout page is accessible.

## Test Data
Shipping address:
- Name: Test User
- Address: Example Street 123
- City: Istanbul
- Country: Turkey
- Postal Code: 34000

Payment details (mock):
- Card Number: 4111 1111 1111 1111 (test card)
- Expiry Date: 12/28
- CVV: 123
- Cardholder Name: Test User

## Test Steps
1. Log in with a valid user account.
2. Add at least one in-stock product to the cart.
3. Navigate to the cart page and click the "Proceed to Checkout" button.
4. On the checkout page, fill in all required shipping address fields with valid data.
5. Enter valid mock payment card details.
6. Click the "Pay" or "Place Order" button.
7. Observe the system response.

## Expected Result
- Payment should be processed successfully in the mock environment.
- User should see an order confirmation page.
- A success message such as "Your order has been placed" should be displayed.
- Order summary should list the correct products and total amount.

## Status
Not Executed
