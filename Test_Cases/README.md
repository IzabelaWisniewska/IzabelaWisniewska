
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
| :--- | :--- | :--- |
| **Test Case ID** | Unique identifier for tracking and traceability | `TC_AUTH_001`, `TC_3D_004` |
| **Title / Summary** | Short, descriptive title explaining what is being tested | *Verify user login with valid credentials* |
| **Module / Feature** | Functional area or component under test | `Authentication`, `Checkout`, `3D Assets` |
| **Priority / Severity** | Importance and business/technical impact of the test | `High` / `Medium` / `Low` |
| **Pre-conditions** | Prerequisites that must be met before test execution | *User is registered; Web application is loaded* |
| **Test Data** | Specific input parameters or asset files required | `Email: test@example.com`, `Model: hero_mesh.fbx` |
| **Test Steps** | Numbered, sequential actions to perform the test | **1.** Open login page<br>**2.** Enter valid email and password<br>**3.** Click "Sign In" button |
| **Expected Result** | The precise outcome indicating test success | *User is redirected to dashboard; 200 OK status code returned* |
| **Actual Result** | Observed behavior during execution *(populated post-execution)* | *Pass / Fail (with attached log/screenshot if failed)* |
| **Design Technique** | QA methodology applied during scenario design | `Equivalence Partitioning`, `BVA`, `Error Guessing` |

---

## Testing Methodology & Standards
Each test case included in this repository follows industry best practices:
* **Traceability:** Clear alignment with functional requirements.
* **Boundary Value Analysis (BVA):** Testing limits on input fields (e.g., password length, discount codes).
* **Clear Structure:** Every case contains **Pre-conditions**, **Steps**, **Test Data**, and **Expected Results**.

> *Note: All examples provided in this section are generic and created for portfolio demonstration purposes.*
