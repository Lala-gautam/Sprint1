# ParaBank Manual Testing Project

This project is a **Manual Software Testing project** performed on the **ParaBank Online Banking Web Application**.

The objective of this project is to validate the application's major banking functionalities, identify defects, verify requirements, and prepare professional software testing documentation.

 Application Under Test

**Application:** ParaBank – Online Banking Application
**Application Type:** Web Application
**Testing Type:** Manual Testing
**Testing Approach:** Black Box Testing

**Application URL:**
https://parabank.parasoft.com/parabank/index.htm

---

## 🎯 Project Objectives

* Verify that the application works according to its requirements.
* Identify functional and usability defects.
* Validate positive and negative scenarios.
* Ensure important banking workflows work correctly.
* Execute manual test cases.
* Record actual and expected results.
* Report identified defects with severity and priority.
* Maintain Requirement Traceability using RTM.
* Prepare an execution summary for the project.

---

## 🧪 Modules Tested

The following major modules were covered:

1. Registration
2. Login
3. Forgot Login Information
4. Accounts Overview
5. Open New Account
6. Transfer Funds
7. Bill Pay
8. Find Transactions
9. Update Contact Information
10. Request Loan
11. Logout
12. Session Security

---

## 🔍 Testing Types / Techniques

The project primarily uses:

* Manual Testing
* Black Box Testing
* Functional Testing
* Positive Testing
* Negative Testing
* Regression Testing
* Validation Testing
* Security-related testing
* End-to-End testing
* Boundary/validation testing

---

## 📁 Project Files

The main project file is:

```text
lala_manual.xlsx
```

The Excel workbook contains the following sheets:

### 1. Test Plan

Defines the overall testing strategy and scope.

It contains:

* Test Plan ID
* Application Name
* Application URL
* Application Type
* Testing Type
* Testing Approach
* In-Scope Modules
* Out-of-Scope Items
* Testing objectives and related planning information

---

### 2. Test Scenario

Contains high-level scenarios that describe **what needs to be tested**.

Example:

```text
Verify that a new user can register successfully with valid details.
```

Scenarios cover different modules such as Registration, Login, Transfer Funds, Bill Pay, Security, and more.

---

### 3. Test Case

Contains detailed test cases used for actual manual execution.

Each test case includes:

* Test Case ID
* Module
* Test Scenario
* Test Steps
* Test Data
* Expected Result
* Actual Result
* Status
* Bug ID

Example:

```text
TC_001

Module: Registration

Scenario:
Verify that a new user can register successfully with valid details.

Expected Result:
Account should be created successfully and the user should be logged in.
```

---

### 4. Defect Report

Contains defects identified during testing.

Each defect contains:

* Bug ID
* Test Case ID
* Module
* Bug Summary
* Severity
* Priority
* Status
* Steps to Reproduce
* Expected Result
* Actual Result

Example defects identified include:

```text
BUG_001
Session ID exposed in page URLs

BUG_002
Account pages accessible using browser Back button after logout

BUG_003
HTTP 500 error when non-numeric transfer amount is entered

BUG_004
Internal error displayed for invalid Find Transactions input
```

---

### 5. Summary Report

Provides an overall view of the testing execution.

It includes:

* Total Test Cases
* Executed Test Cases
* Passed Test Cases
* Failed Test Cases
* Pass Rate
* Total Bugs Found
* Module-wise execution summary

The report uses Excel formulas to calculate execution statistics automatically.

---

### 6. RTM – Requirement Traceability Matrix

The RTM connects requirements with test scenarios and test cases.

It helps ensure that every requirement has appropriate test coverage.

The RTM contains:

* Requirement ID
* Requirement Description
* Module
* Test Scenario ID
* Test Case ID
* Test Case Description
* Execution Status

Example:

```text
REQ-001
User must be able to register with valid details.

Mapped Test Case:
TC_001
```

---

## 🐞 Defect Management

Defects are documented using standard QA fields.

### Severity

Severity represents the **impact of the defect on the application**.

Examples:

* Critical
* High
* Medium
* Low

### Priority

Priority represents **how urgently the defect should be fixed**.

Examples:

* High
* Medium
* Low

Example:

```text
Bug: Application crashes when non-numeric transfer amount is entered.

Severity: High
Priority: Medium
Status: Open
```

---

## 🔄 Test Execution Process

The testing process followed in this project is:

```text
Requirement Analysis
        ↓
Test Planning
        ↓
Test Scenario Creation
        ↓
Test Case Design
        ↓
Test Data Preparation
        ↓
Test Case Execution
        ↓
Defect Identification
        ↓
Defect Reporting
        ↓
Retesting
        ↓
Regression Testing
        ↓
Test Summary Report
        ↓
Test Closure
```

---

## 📊 Project Deliverables

The project contains the following QA deliverables:

| Deliverable    | Description                        |
| -------------- | ---------------------------------- |
| Test Plan      | Defines testing scope and approach |
| Test Scenarios | High-level testing scenarios       |
| Test Cases     | Detailed executable test cases     |
| Defect Report  | Documents identified defects       |
| Summary Report | Provides execution statistics      |
| RTM            | Maps requirements to test cases    |

---

## 🛠️ Tools Used

* **Microsoft Excel** – Test documentation and reporting
* **Web Browser** – Application testing
* **ParaBank** – Application Under Test
* **Manual Testing Techniques** – Test execution and defect identification

---

## 📈 Testing Results

The Excel workbook contains an automatically calculated **Summary Report** that provides:

* Total number of test cases
* Number of executed test cases
* Number of passed test cases
* Number of failed test cases
* Pass percentage
* Number of defects identified
* Module-wise testing statistics

The results can be updated automatically by changing the execution status in the **TestCase** sheet.

---

## 👨‍💻 My Role

**Role:** Manual Software Tester

Responsibilities performed in this project:

* Analyzed application requirements.
* Prepared test scenarios.
* Designed detailed test cases.
* Prepared positive and negative test data.
* Executed test cases manually.
* Compared actual results with expected results.
* Identified and documented defects.
* Assigned severity and priority.
* Prepared RTM.
* Prepared test execution summary.
* Performed security and session-related validation.

---

## 💡 Key Learning

Through this project, I gained practical understanding of:

* Software Testing Life Cycle (STLC)
* Test Case Design
* Test Scenario Creation
* Functional Testing
* Negative Testing
* Defect Life Cycle
* Bug Reporting
* Severity vs Priority
* Requirement Traceability Matrix
* Test Execution
* Test Summary Reporting
* Basic Security Testing
* Real-world manual testing documentation

---

## 🚀 How to Use This Project

1. Download or clone this repository.
2. Open `lala_manual.xlsx`.
3. Start with the **TestPlan** sheet.
4. Review the **TestScenario** sheet.
5. Execute test cases from the **TestCase** sheet.
6. Record the actual result and status.
7. If a defect is found, document it in **DefectReport**.
8. Review requirement coverage in **RTM**.
9. Check overall results in **SummaryReport**.

---

## 📂 Recommended Repository Structure

```text
ParaBank-Manual-Testing/
│
├── README.md
│
├── Test-Documents/
│   └── lala_manual.xlsx
│
└── Screenshots/
    └── application-screenshots
```

---

## ⚠️ Disclaimer

This project is created for **educational and portfolio purposes**. ParaBank is used as the application under test for demonstrating manual software testing concepts and documentation.

---

## 📬 Contact

**Software Tester | Manual Testing**

This project demonstrates practical knowledge of manual testing, test documentation, defect reporting, and QA processes.
