
# Test Cases Documentation

This directory contains sample functional test cases demonstrating structured test design, clear pre-conditions, step-by-step verification, and expected outcomes.

---

## Overview of Test Scenarios

* **Web** - test cases for the web application:
  
  * **Login** - Positive and negative authentication paths, input validation, password reset flow, account lockout rules
  
  * **UI Elements** - Button states, component visibility, form field interactions, layout responsiveness, navigation accuracy
  
  * **Localization** - Language switching, translated string completeness, text truncation checks, date and currency formatting

---
## Test Case Standard Structure

All test cases in this repository follow a standardized, structured layout to ensure clarity, repeatability, and ease of execution.

| Attribute | Description | Example / Allowed Values |
| :---: | :---: | :---: |
| <div align="left">**Test Case ID**  | <div align="left">Unique identifier for tracking and traceability | <div align="left">`TC_AUTH_001`, `TC_UI_004` |
| <div align="left">**Title/Summary**  | <div align="left">Short, descriptive title explaining what is being tested | <div align="left">*Verify user login with valid credentials* |
| <div align="left">**Template**  | <div align="left">Formatting type: Steps + Results | |
| <div align="left">**Type**  | <div align="left">Type of testing | <div align="left">`Security`, `Functional`|
| <div align="left">**Status**  | <div align="left">Lifecycle status | <div align="left">`Draft`, `Approved`, `Review`|
| <div align="left">**Defects**  | <div align="left">Linked issues or defect IDs | |
| <div align="left">**Execution Status** &nbsp;| <div align="left">Outcome | <div align="left">`Passed`, `Failed`, `Blocked`, `Not Executed`, `Retest`, `Skipped` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
| <div align="left">**Assigned To**  | <div align="left">Responsible QA Engineer | |
| <div align="left">**Module/Feature**  | <div align="left">Functional area or component under test | <div align="left">`Authentication`, `Checkout` |
| <div align="left">**Priority/Severity**  | <div align="left">Importance and business/technical impact of the test | <div align="left">`High` / `Medium` / `Low` |
| <div align="left">**Pre-conditions**  | <div align="left">Prerequisites that must be met before test execution | <div align="left">*User is registered; Web application is loaded* |
| <div align="left">**Test Data**  | <div align="left">Specific input parameters or asset files required | <div align="left">`Email: test@example.com`, `Model: hero_mesh.fbx` |
| <div align="left">**Test Steps**  | <div align="left">Numbered, sequential actions to perform the test | <div align="left">**1.** Open login page<br>**2.** Enter valid email and password<br>**3.** Click "Sign In" button |
| <div align="left">**Expected Result**  | <div align="left">The precise outcome indicating test success | <div align="left">*User is redirected to dashboard; 200 OK status code returned* |
| <div align="left">**Actual Result**  | <div align="left">Observed behavior during execution *(populated post-execution)* | <div align="left">*Pass / Fail (with attached log/screenshot if failed)* |

---

## Testing Methodology & Standards
Each test case included in this repository follows industry best practices:
* **Traceability:** Clear alignment with functional requirements.
* **Boundary Value Analysis (BVA):** Testing limits on input fields (e.g., password length, discount codes).
* **Clear Structure:** Every case contains **Pre-conditions**, **Steps**, **Test Data**, and **Expected Results**.

> *Note: All examples provided in this section are generic and created for portfolio demonstration purposes.*

