# Manual Testing

This folder contains my manual testing documentation for SauceDemo.

## Files
- `Sauce Demo - Manual Testing Portolio.pdf` (test plan + manual test suite + execution summary) :contentReference[oaicite:2]{index=2}

## What’s inside the PDF
- Test Plan v1.0 with scope, approach, environment, entry/exit criteria, and deliverables :contentReference[oaicite:3]{index=3}
- 55 manual test cases across:
  - Login and session
  - Inventory and sorting
  - Cart
  - Checkout
  - Menu and footer
  - Non-functional checks (performance, responsive, accessibility, security)
  - Edge scenarios :contentReference[oaicite:4]{index=4}
- Execution summary: 55 executed, 48 passed, 7 failed :contentReference[oaicite:5]{index=5}

## Notable findings (examples)
- Data quality: product name mismatch and incorrect alt text :contentReference[oaicite:6]{index=6}
- Usability: required fields have no visual required indicator :contentReference[oaicite:7]{index=7}
- Accessibility: missing visible keyboard focus indicator :contentReference[oaicite:8]{index=8}
- Security: username stored in cookies in clear text :contentReference[oaicite:9]{index=9}
- Formatting: totals show more than 2 decimal places :contentReference[oaicite:10]{index=10}

## How this connects to automation
These manual cases are written so they can be reused as a base for UI automation (Cypress/Playwright) and regression checks. :contentReference[oaicite:11]{index=11}
