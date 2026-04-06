# Playwright Automation Framework

A robust, scalable End-to-End test automation framework 
built with Playwright and TypeScript.

## 🛠️ Tech Stack

- [Playwright](https://playwright.dev/) - E2E Testing Framework
- TypeScript - Programming Language
- Page Object Model - Design Pattern
- GitHub Actions - CI/CD Pipeline
- Allure - Test Reporting

## 📁 Project Structure

├── tests/
│   ├── e2e/
│   └── api/
├── pages/
├── fixtures/
├── utils/
├── test-data/
├── .github/
│   └── workflows/
├── playwright.config.ts
└── package.json

## ✅ Features

- Page Object Model architecture
- Custom fixtures
- API testing
- Visual regression testing
- CI/CD with GitHub Actions
- Allure reporting

## 🚀 Getting Started

### Prerequisites
- Node.js >= 18
- npm >= 8

### Installation
```bash
git clone https://github.com/iboujhair-stack/playwright-automation-framework
cd playwright-automation-framework
npm install
npx playwright install
```

### Run Tests
```bash
# Run all tests
npx playwright test

# Run specific test file
npx playwright test tests/e2e/login.spec.ts

# Run with UI mode
npx playwright test --ui

# Run with specific browser
npx playwright test --project=chromium
```

## 📊 Reports
```bash
npx allure serve allure-results
```

## 👤 Author

**Oussama** - QA Automation Engineer
- GitHub: [@iboujhair-stack](https://github.com/iboujhair-stack)
- LinkedIn: [your-linkedin-url]
