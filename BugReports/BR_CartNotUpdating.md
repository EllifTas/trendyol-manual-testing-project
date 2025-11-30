# Bug Report: Cart Item Count Mismatch Between Icon and Cart Page

## Bug ID
BR_002

## Title
Cart icon shows incorrect item count after adding a product.

## Environment
- Web: Chrome 120+
- OS: macOS / Windows
- App Version: N/A (Simulation)

## Severity
Major

## Priority
Medium

## Precondition
User is on a product detail page of an in-stock product.

## Steps to Reproduce
1. Navigate to an in-stock product detail page.
2. Click the “Add to Cart” button once.
3. Observe the cart icon in the top navigation bar.
4. Open the cart page.
5. Compare the item count displayed on the cart icon vs the count displayed in the cart page.

## Expected Result
- Cart icon should show **1**.
- Cart page should show **1**.
- Both counts must match.

## Actual Result
- Cart icon shows **0**.
- Cart page shows **1**.
- Counts are inconsistent.

## Screenshot / Attachment
(N/A)

## Notes
Common UI update issue. May be caused by async cart update or client-side cache.

