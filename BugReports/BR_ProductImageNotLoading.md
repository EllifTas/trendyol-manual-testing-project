
# Bug Report: Product Image Not Loading on Product Listing Page

## Bug ID
BR_003

## Title
Product image fails to load on the product listing page.

## Environment
- Web: Chrome 120+
- OS: macOS / Windows
- App Version: N/A (Simulation)

## Severity
Minor (could be Major depending on frequency)

## Priority
Low / Medium (depends on UX impact)

## Precondition
User is on a category or search results page.

## Steps to Reproduce
1. Navigate to a product listing page (e.g., "Shoes" category).
2. Scroll through the products.
3. Observe product thumbnails.
4. Identify product cards with missing or broken images.

## Expected Result
- All product images should load correctly.
- No broken image icons should appear.

## Actual Result
- At least one product shows a **broken image icon** (image placeholder).
- The product displays only name and price but no image.

## Screenshot / Attachment
(N/A)

## Notes
This issue impacts user trust and product visibility.  
Often caused by:
- Incorrect image URL  
- CDN timeouts  
- Missing image file  
- Slow network not handled properly
