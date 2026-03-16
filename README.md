
# LD Tax Portal QA Testing

This repository contains manual QA testing documentation prepared for the LD Tax Portal: https://www.ldtax.gov.bd/

The project focuses on the Registration and Login modules and presents a structured set of testing documents created to evaluate form validation, user flow, and basic usability of the application.

## Project Summary

The goal of this project is to document and organize manual testing activities for key authentication features of the LD Tax Portal. The work includes test planning, scenario preparation, detailed test case design, execution support, and improvement recommendations.

This project was prepared as part of a practical QA documentation exercise to reflect a real-world testing workflow.

## Modules Covered

- Registration
- Login

## Scope of Work

The testing documentation in this repository covers:

- account type selection between Citizen and Organization
- registration through Mobile and Email
- login through Mobile and Email
- input validation for name, mobile number, email, password, and captcha
- error message handling for blank and invalid inputs
- captcha visibility and refresh behavior
- navigation between Login, Register, and Forgot Password options
- validation behavior while switching between tabs and options
- successful registration and login flow checks

## Testing Approach

The project was prepared using manual testing techniques with a focus on functional behavior, validation rules, UI feedback, and navigation flow.

### Testing types included

- Functional Testing
- Validation Testing
- UI Testing
- Navigation Testing
- Positive Testing
- Negative Testing

## Deliverables

The repository includes the following QA artifacts:

- Test Plan
- Test Scenarios
- Test Cases
- Recommendations
- Bug Screenshots
- Execution Notes

## Documentation Structure

The main workbook contains organized QA sheets for:

- test planning
- scenario listing
- detailed test case documentation
- recommendation tracking
- supporting notes and remarks

Each test case is documented with the following fields:

- SL
- Module
- Type of Testing
- Features
- Test Cases
- Expected Result
- Actual Result
- Test Data
- Reproducing Steps
- Bug Screenshot
- Dev Comments
- Final Status
- Remarks

## Repository Structure

```text
ldtax-qa-testing/
├── README.md
├── ldtax_updated_workbook.xlsx
├── screenshots/
│   ├── registration/
│   └── login/
├── bug-reports/
├── reports/
└── docs/
