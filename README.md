# Playwright Login Test Suite — Saucedemo

Automated end-to-end login tests for [saucedemo.com](https://www.saucedemo.com) built with Playwright and JavaScript.

## What This Tests

- Successful login with valid credentials
- Failed login with invalid credentials
- Locked out user error message validation

## Tech Stack

- Playwright
- JavaScript
- Node.js
- GitHub Actions (CI/CD)

## How To Run

Install dependencies:

```bash
npm install
```

Run tests on Chromium:

```bash
npx playwright test tests/login.test.js --project=chromium
```

View HTML report:

```bash
npx playwright show-report
```

## Test Results

3 tests — 3 passed on Chromium and Firefox.

## About

Built as part of my QA automation portfolio. I have 5 years of QA experience in fintech (M1 Finance, JPMorgan Chase) and am expanding into test automation.