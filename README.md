# 🎭 Playwright Tests Practice

![Playwright](https://img.shields.io/badge/Playwright-Automation-2EAD33?logo=playwright&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-181717?logo=github)

## 📖 About the Project

This repository contains my hands-on practice with **Playwright**, focusing on End-to-End (E2E) test automation using JavaScript.

The goal of this project is to strengthen my automation skills by implementing real-world testing scenarios while following Playwright best practices.

---

## 🚀 Technologies

- 🎭 Playwright
- ☕ JavaScript
- 🟢 Node.js
- 🌐 Git & GitHub
- 💻 Visual Studio Code

---

## 📂 Project Structure

```text
playwright-tests-practice/
│
├── tests/
│   └── e2e-ecommerce.spec.js
│
├── playwright.config.js
├── package.json
├── package-lock.json
└── README.md
```

---

## ✅ Test Scenarios

### Authentication

- Login with valid credentials
- Login with invalid credentials
- Required field validation
- Logout

### Product Validation

- Verify product listing
- Verify empty product list
- Backend response mocking
- Unauthorized access (HTTP 403)
- Error handling scenarios

### Playwright Concepts

- Locators
- Assertions
- Hooks (`beforeEach`)
- Route Interception
- API Mocking
- HTML Reports
- Debugging
- Network Inspection

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/Maky-GloryQA/playwright-tests-practice.git
```

Go to the project folder

```bash
cd playwright-tests-practice
```

Install dependencies

```bash
npm install
```

Install Playwright browsers

```bash
npx playwright install
```

---

## ▶️ Running the Tests

Run all tests

```bash
npx playwright test
```

Run in headed mode

```bash
npx playwright test --headed
```

Run using Playwright UI

```bash
npx playwright test --ui
```

Run a specific test file

```bash
npx playwright test tests/e2e-ecommerce.spec.js
```

---

## 📊 HTML Report

After running the tests, open the HTML report:

```bash
npx playwright show-report
```

---

## 📚 Skills Practiced

- End-to-End Testing
- UI Automation
- Assertions
- Test Organization
- Hooks
- Backend Mocking
- Route Interception
- HTTP Status Validation
- DOM Inspection
- Debugging
- Git Workflow

---

## 📈 Learning Progress

### ✔️ Completed

- [x] Playwright Installation
- [x] JavaScript Basics
- [x] Locators
- [x] Assertions
- [x] Hooks
- [x] Login Tests
- [x] Product Tests
- [x] Backend Mocking
- [x] HTTP Error Scenarios
- [x] HTML Reports

### 🔄 Coming Next

- [ ] Page Object Model (POM)
- [ ] Fixtures
- [ ] Data-Driven Testing
- [ ] API Testing
- [ ] Authentication
- [ ] Cross-Browser Testing
- [ ] CI/CD with GitHub Actions

---

## 🎯 Purpose

This repository is part of my QA Automation learning journey.

Each new commit represents a new concept learned and applied using Playwright.

The project will continue to grow as I explore more advanced automation techniques.

---

## 👩‍💻 Author

**McGlory Tovar**

QA Analyst | Learning QA Automation

📍 Argentina

🔗 GitHub: https://github.com/Maky-GloryQA
