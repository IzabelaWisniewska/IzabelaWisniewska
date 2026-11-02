
# Test Cases Documentation

This directory contains sample functional test cases demonstrating structured test design, clear pre-conditions, step-by-step verification, and expected outcomes.

---

## 📂 Overview of Test Scenarios

| File Name | Module / Feature | Description |
| :--- | :--- | :--- |
| `TC_01_Authentication.md` | User Login & Registration | Functional scenarios covering positive paths, invalid credentials, and security limits. |
| `TC_02_Checkout_Process.md` | E-commerce / Cart | End-to-end shopping flow, price calculations, and boundary value checks. |
| `TC_03_3D_Asset_Validation.md` | Graphic & 3D QA | Technical verification scenarios for models, textures, and animations. |

---
## 📐 Test Case Standard Structure

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

### 📝 Example Test Case Scenario

#### `TC_3D_001` - Visual & Mesh Validation of 3D Model
* **Priority:** High
* **Pre-conditions:** Asset `hero_character_v2.fbx` loaded in Blender 4.x / target engine.
* **Steps:**
  1. Inspect geometry mesh density and topology.
  2. Verify UV mapping for texture stretching.
  3. Validate texture resolution and material assignment.
* **Expected Result:** Mesh topology has no non-manifold geometry, UVs are packed correctly without overlapping errors, and material shaders render without artifacts.

---

## 🛠️ Testing Methodology & Standards
Each test case included in this repository follows industry best practices:
* **Traceability:** Clear alignment with functional requirements.
* **Boundary Value Analysis (BVA):** Testing limits on input fields (e.g., password length, discount codes).
* **Clear Structure:** Every case contains **Pre-conditions**, **Steps**, **Test Data**, and **Expected Results**.

> *Note: All examples provided in this section are generic and created for portfolio demonstration purposes.*
