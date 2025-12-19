# Manual Testing

This folder contains my manual testing documentation for SauceDemo.

## Files
- `Sauce Demo - Manual Testing Portolio.pdf` (test plan + manual test suite + execution summary)

## What’s inside the PDF
- Test Plan v1.0 with scope, approach, environment, entry/exit criteria, and deliverables
- 55 manual test cases across:
  - Login and session
  - Inventory and sorting
  - Cart
  - Checkout
  - Menu and footer
  - Non-functional checks (performance, responsive, accessibility, security)
  - Edge scenarios 
- Execution summary: 55 executed, 48 passed, 7 failed 

## Notable findings (examples)
- Data quality: product name mismatch and incorrect alt text 
- Usability: required fields have no visual required indicator 
- Accessibility: missing visible keyboard focus indicator 
- Security: username stored in cookies in clear text 
- Formatting: totals show more than 2 decimal places 

## How this connects to automation
These manual cases are written so they can be reused as a base for UI automation (Cypress/Playwright) and regression checks. 
