# Bug Report: Search Results Not Matching the Entered Keyword

## Bug ID
BR_004

## Title
Search results display irrelevant products that do not match the user’s search keyword.

## Environment
- Web: Chrome 120+
- OS: macOS / Windows
- App Version: N/A (Simulation)
- Network: Stable

## Severity
Major

## Priority
High

## Precondition
User is on the homepage and search functionality is available.

## Steps to Reproduce
1. Go to the homepage.
2. Type the keyword **"black shoes"** in the search bar.
3. Press Enter or click the search icon.
4. Observe the product listing results.

## Expected Result
- All products displayed should be relevant to the keyword **“black shoes”**.
- At minimum, the product color should match (“black”) and category should match (“shoes”).

## Actual Result
- Several products shown are **unrelated**, such as:
  - White sneakers
  - Brown boots
  - Handbags
- Some products do not contain any keyword-related attributes.

## Screenshot / Attachment
(N/A)

## Notes
This is a critical relevance issue.  
Possible causes:
- Search algorithm mismatch  
- Incorrect indexing  
- Category/attribute tagging errors  
- Caching issue causing inconsistent result sets
