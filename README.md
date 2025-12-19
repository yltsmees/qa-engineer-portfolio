# QA Engineer Portfolio (Hub)

This repo is my portfolio hub. It brings my automation projects together and stores my manual testing documentation in one place.

## Quick links

### UI automation (Cypress, SauceDemo)
Repo: https://github.com/yltsmees/saucedemo-cypress-portfolio

What you’ll find:
- Cypress 15.x (JavaScript), Node.js 18+
- Feature-based specs (login, inventory, cart, checkout, non-functional)
- Page Object Model (POM), fixtures, and custom commands
- Clear test IDs (example: `SD_LOGIN_01`, `SD_CHECKOUT_07`)

### API automation (Postman + Newman, GoREST)
Repo: https://github.com/yltsmees/gorest-postman-newman-portfolio

What you’ll find:
- Postman collection + Newman runs (local + GitHub Actions)
- HTML report output
- Token-safe environment file (token stays empty in the repo)
- Chained requests using environment variables (`user_id`, `post_id`, `comment_id`)

## Manual testing
Go to: `Manual/`

I keep test plans, test cases, and supporting notes here (PDF and/or spreadsheets). This makes it easy to review without opening multiple repos.

## Repo structure

```text
qa-engineer-portfolio/
  README.md
  Manual/
    README.md
  Automation/
    README.md
    UI/
      README.md
    API/
      README.md
