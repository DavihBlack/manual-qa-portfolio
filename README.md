# Manual QA Portfolio

This repository contains practical Manual QA projects demonstrating how I approach test planning, risk analysis, test design, execution, defect reporting, evidence collection, and traceability.

The projects use public applications so the full testing workflow can be shared without exposing confidential client information.

For an overview of my broader QA experience, skills, services, and other portfolio areas, visit:

[Main QA Portfolio](https://github.com/DavihBlack/qa-portfolio)

---

## Projects

### SauceDemo

Manual testing project focused on product validation, cart functionality, and consistency across Product Listing Page (PLP) and Product Detail Page (PDP).

The project includes:

- Scope and risk analysis
- Entry and exit criteria
- Test data
- Test case design
- Positive and negative scenarios
- Test execution
- Defect reporting
- Supporting evidence
- Regression and retesting activities

#### Test Cycle

[View SauceDemo Test Cycle Overview](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/saucedemo/test-cycles/saucedemo-test-cycle-overview.md)

#### Test Execution

[View SauceDemo Execution Report](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/saucedemo/test-cases/test-execution-report-saucedemo.md)

#### Test Cases

- [Product Validation — PLP vs PDP](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/saucedemo/test-cases/tc01-product-validation-test-case.md)
- [Remove Product from Cart](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/saucedemo/test-cases/tc02-remove-button-test-case.md)
- [Add Product to Cart](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/saucedemo/test-cases/tc03-add-to-cart.md)

#### Defects

- [PLP displays incorrect product image and inconsistent pricing compared to PDP for 'Sauce Labs Backpack'](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/saucedemo/bug-reports/swag-labs-image-price-mismatch.md)
- [Remove Button Does Not Remove Product From the Cart in PLP and PDP](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/saucedemo/bug-reports/saucedemo-remove-button.md)

---

### Buggy Cars Rating

Manual testing project focused on navigation behavior, system stability, and validation of key user interactions.

The project includes:

- Scope and risk analysis
- Entry and exit criteria
- Test data
- Test case design
- Test execution
- Defect reporting
- Supporting evidence

#### Test Cycle

[View Buggy Cars Test Cycle Overview](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/buggy-cars/test-cycles/buggy-cars-test-cycle-overview.md)

#### Test Execution

[View Buggy Cars Execution Report](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/buggy-cars/test-cases/test-execution-report-buggy-cars.md)

#### Test Cases

- [Buggy Cars Navigation](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/buggy-cars/test-cases/tc-01-buggy-cars-navigation.md)
- [Popular Make Navigation](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/buggy-cars/test-cases/tc-002-popular-make.md)
- [Overall Rating Navigation](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/buggy-cars/test-cases/tc-003-overall-rating.md)

#### Defects

- [Clicking Any Car Model Causes the Page to Load Indefinitely](https://github.com/DavihBlack/manual-qa-portfolio/blob/main/buggy-cars/bug-reports/buggy-cars-model-loading-issue.md)

---

## What These Projects Demonstrate

The artifacts in this repository demonstrate practical experience with:

- Risk-based test planning
- Test scope definition
- Test condition and scenario design
- Structured test case creation
- Positive, negative and edge-case testing
- Test execution and result tracking
- Defect identification and investigation
- Clear reproduction steps
- Severity and impact assessment
- Evidence collection using screenshots and recordings
- Retesting and regression validation
- Traceability between test activities and identified defects

---

## Repository Structure

```text
manual-qa-portfolio/
│
├── buggy-cars/
│   ├── bug-reports/
│   ├── screen-records/
│   ├── screenshots/
│   ├── test-cases/
│   └── test-cycles/
│
├── saucedemo/
│   ├── bug-reports/
│   ├── screen-records/
│   ├── screenshots/
│   ├── test-cases/
│   └── test-cycles/
│
└── README.md
```

Each project is kept separate so its test cycle, execution evidence, test cases and defects can be reviewed as a complete QA workflow.

---

## Main QA Portfolio

This repository focuses specifically on Manual Testing.

For my complete QA portfolio, including professional testing experience, testing approach, technical skills, automation, API testing, database validation, and QA services:

[View Main QA Portfolio](https://github.com/DavihBlack/qa-portfolio)