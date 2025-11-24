Test Plan – Trendyol Web Application
Version: 1.0
Author: Elif Taş
Date: November 2025

1. Introduction
This Test Plan defines the scope, approach, resources, and schedule of testing activities for Trendyol’s web application.
The objective is to ensure the quality and stability of core user journeys such as login, product search, product details, and shopping cart operations.

2. Scope of Testing
In-Scope
Login functionality
Product search, filtering, and product detail pages
Shopping cart operations (add/remove/update items)
Checkout redirection (mock environment)
Basic UI and navigation checks
Error messages & validation rules
API response validation (high-level)
Out of Scope
Real payment validation
Integration with external payment providers
Mobile application (native)
Performance and load testing (covered in separate project)

3. Test Approach
Testing will be conducted manually using functional, smoke, and basic regression techniques.
The approach includes:
Positive and negative test scenarios
UI/UX validation
Form validation
Error message validation
Test data-driven checks
Retesting and regression cycles for fixed defects
Bug tracking will be performed using Jira format (simulated).

4. Test Types
Smoke Testing
Functional Testing
Regression Testing
UI Testing
Error & Validation Testing

5. Test Environment
Browsers
Chrome (latest)
Firefox (latest)
Safari (MacOS)
Edge (optional)
Devices
Desktop
Mobile Web:
iOS Safari
Android Chrome
Test Data
Predefined user accounts
Demo product data

6. Test Deliverables
Test Plan (this document)
Test Case Set (Login, Search, Add to Cart, Checkout)
Smoke Test Checklist
Bug Reports
Test Summary Report (optional)

7. Entry Criteria
Testing may begin when:
Required test environment is stable
Test data is prepared
Functional requirements are understood
Core features are accessible

8. Exit Criteria
Testing is complete when:
All critical test cases are executed
No open blocker or critical bugs remain
Smoke suite fully passes
All major regressions have been retested

9. Risks & Assumptions
Risks
Unstable test environment
Missing or inaccurate requirements
Delayed defect fixes
Assumptions
Requirements will remain consistent
Test data will not change during the cycle
Browsers/devices are available for testing

10. Tools
Chrome DevTools
Jira (bug report format only)
Markdown documentation in GitHub
Postman (for verifying API behaviour at a high level)

11. Schedule
Activity	Date
Test planning	Week 1
Test case design	Week 1
Test execution	Week 2
Defect reporting & retesting	Week 2
