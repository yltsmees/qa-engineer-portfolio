\# UI Automation (Cypress)



\## Project

SauceDemo Cypress Portfolio  

https://github.com/yltsmees/saucedemo-cypress-portfolio



\## What this project demonstrates

\- End-to-end UI automation with Cypress (JavaScript)

\- Maintainable structure using:

&nbsp; - Feature-based specs

&nbsp; - Page Object Model (POM)

&nbsp; - Fixtures for test data

&nbsp; - Custom Cypress commands



\## What the tests cover (high level)

\- Login: positive + negative + session checks

\- Inventory: sorting, navigation, state behaviour

\- Cart: add/remove flows, badge count, totals

\- Checkout: validation, overview math, completion

\- Non-functional/UX checks: formatting, storage/url safety, stability checks



Some tests are marked as \*\*EXPECTED BUG\*\* when they document known issues in the demo app.



\## Run locally (quick)

```bash

git clone https://github.com/yltsmees/saucedemo-cypress-portfolio.git

cd saucedemo-cypress-portfolio

npm install



\# GUI

npm run cy:open



\# Headless

npm run cy:run



