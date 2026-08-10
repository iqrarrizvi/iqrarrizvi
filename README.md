# Iqrar Rizvi

QA Analyst transitioning into QA Automation Engineering. I build test frameworks, automate reporting workflows, and write structured end-to-end test coverage across UI, API, and multi-user flows.

---

## Tech Stack

**Test Automation**
- Playwright (JavaScript / TypeScript) — E2E, API, multi-user flows, visual regression
- Page Object Model, reusable action helpers, custom assertions
- Cucumber / Gherkin — BDD feature files wired to Playwright step definitions
- axe-core — WCAG 2.1 AA accessibility scanning
- k6 — performance load testing (ramp, spike, soak patterns)
- Pact.js — consumer-driven contract testing

**AI & Test Data**
- Claude API (`@anthropic-ai/sdk`) — AI-assisted test generation
- faker.js — programmatic test data generation (JSON / CSV / SQL export)

**Backend / Scripting**
- Node.js, Express
- PowerShell — document and report generation via COM automation
- SQL Server — query-driven reporting and data validation

**CI/CD & Tooling**
- Azure DevOps Pipelines — YAML pipeline authoring, artifact publishing, JUnit results
- GitHub Actions — smoke → gates → regression workflows, k6 load tests, contract artifact sharing
- dotenv — credential management via environment variables

---

## Featured Projects

### [playwright-demo-suite](https://github.com/iqrarrizvi/playwright-demo-suite)
Playwright E2E suite targeting a public demo storefront — 14 tests covering login, inventory, cart, and full checkout. Page Object Model with a reusable action dispatcher. GitHub Actions CI badge reflects live test results.

**Stack:** Playwright · Node.js · GitHub Actions

---

### playwright-e2e-suite *(available on request)*
Playwright automation framework covering document management UI workflows, multi-user approval flows, and API contract tests. Structured with Page Object Model, reusable helpers, and an Azure Pipelines CI config.

**Stack:** Playwright · Node.js · Azure DevOps · pdf2json · Tesseract.js · mssql

---

### [query-report-builder](https://github.com/iqrarrizvi/query-report-builder)
Node.js web app that queries a SQL Server data warehouse and generates formatted Excel reports via ExcelJS. Supports 10 configurable report types with a browser-based UI.

**Stack:** Node.js · Express · SQL Server · ExcelJS · dotenv

---

## Currently Building

Working through a QA portfolio series — each repo below demonstrates a different layer of test engineering:

| Repo | Focus |
|---|---|
| [`playwright-demo-suite`](https://github.com/iqrarrizvi/playwright-demo-suite) | Playwright on a public demo app — runnable by anyone |
| [`api-test-suite`](https://github.com/iqrarrizvi/api-test-suite) | REST API testing — auth, CRUD, schema validation (Playwright) |
| [`postman-api-collection`](https://github.com/iqrarrizvi/postman-api-collection) | Same API coverage via Postman + Newman CI |
| [`accessibility-test-suite`](https://github.com/iqrarrizvi/accessibility-test-suite) | Playwright + axe-core WCAG 2.1 AA compliance checks |
| [`multi-user-flow-patterns`](https://github.com/iqrarrizvi/multi-user-flow-patterns) | Parallel browser context patterns — concurrent sessions, cart isolation, simultaneous checkout |
| [`k6-load-test-templates`](https://github.com/iqrarrizvi/k6-load-test-templates) | k6 performance scripts — ramp, spike, soak with CI-aware durations |
| [`bdd-playwright-demo`](https://github.com/iqrarrizvi/bdd-playwright-demo) | Playwright + Cucumber BDD — Gherkin feature files wired to Page Objects |
| [`ai-test-generator`](https://github.com/iqrarrizvi/ai-test-generator) | CLI tool that generates Playwright test files from plain-English feature descriptions using the Claude API |
| [`visual-regression-suite`](https://github.com/iqrarrizvi/visual-regression-suite) | Playwright pixel-level visual regression — detects unintended UI changes across releases |
| [`test-data-factory`](https://github.com/iqrarrizvi/test-data-factory) | CLI test data generator using faker.js — exports to JSON, CSV, or SQL INSERT statements |
| [`contract-testing-demo`](https://github.com/iqrarrizvi/contract-testing-demo) | Consumer-driven contract testing with Pact.js — frontend contracts verified against a live REST API provider |
| [`qa-for-ai-features`](https://github.com/iqrarrizvi/qa-for-ai-features) | QA patterns for AI features — response schema, latency SLAs, content safety, and guardrail validation |
| [`qa-practice-api`](https://github.com/iqrarrizvi/qa-practice-api) | Purpose-built REST API (auth, users, products, orders) with 32 Playwright API tests — built to be tested |
| [`test-results-dashboard`](https://github.com/iqrarrizvi/test-results-dashboard) | React dashboard that visualises Playwright JSON reports — suite charts, slowest tests, searchable test list |
| [`security-test-patterns`](https://github.com/iqrarrizvi/security-test-patterns) | OWASP Top 10 security patterns in Playwright — header checks, XSS/injection, auth bypass, sensitive data exposure |
| [`mutation-testing-demo`](https://github.com/iqrarrizvi/mutation-testing-demo) | Stryker mutation testing on a shopping cart module — 221 mutants, 89% mutation score, surviving mutants documented |
| [`graphql-test-suite`](https://github.com/iqrarrizvi/graphql-test-suite) | Playwright API tests for GraphQL — queries, variables, filtering, errors, introspection; includes a self-contained mock server |

---

## Contact

[LinkedIn](https://linkedin.com/in/iqrar-rizvi)
