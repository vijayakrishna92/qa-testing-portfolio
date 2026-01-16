# qa-testing-portfolio
This repository contains manual, API, and AI testing projects created to practice real-world software testing concepts including test case design, defect reporting, and validation of functional and edge-case scenarios.


# QA Testing Portfolio

## 📌 Project Overview

This repository contains my **QA Testing Portfolio**, created as part of my career transition into the **Software Testing / QA / AI Tester** domain. The project demonstrates my hands-on experience in **manual testing** and **API testing**, along with structured test documentation and defect reporting following industry-standard practices.

The focus of this portfolio is to show **how I think as a tester**, how I design test cases, execute them, identify defects, and document findings clearly.

---

## 🧪 Project 1: Manual and API Testing of an Authentication System

### 🔹 Objective

To validate the functionality, reliability, and basic security aspects of an authentication system by performing:

* Manual UI testing
* API testing using Postman

---

## 🔹 Manual Testing

### Scope

Manual testing was performed on the **Login module** of a web-based application called https://opensource-demo.orangehrmlive.com/web/index.php/auth/login.

### Types of Testing Performed

* Functional Testing
* Negative Testing
* Validation Testing
* Basic Security Testing (SQL injection attempts)
* Session Management Testing

### Deliverables

* **Test Cases:** Detailed manual test cases with preconditions, test steps, expected results, actual results, and pass/fail status
* **Bug Reports:** Defects identified during execution, logged with severity and priority

📁 Location:

```
/manual-testing/
 └── Test_Scenarios.xlsx
 ├── Test_Cases.xlsx
 └── Bug_Report.xlsx
```

### Key Highlights

* Designed and executed **17 manual test cases** for the login module
* Identified and logged defects related to improper handling of SQL injection inputs
* Verified access control by testing direct URL access without authentication

---

## 🔹 API Testing

### Scope

API testing was performed to validate backend behavior independently of the UI.

### Tools Used

* **Postman** – for sending API requests and validating responses

### Activities Performed

* Created API test scenarios and test cases for https://fakestoreapi.com/
* Tested GET and POST APIs
* Validated:

  * HTTP status codes
  * Response body structure
  * Error handling for invalid inputs
* Captured Postman execution screenshots as proof of testing

📁 Location:

```
/api-testing/
 ├── API_Test_Scenarios.xlsx
 ├── API_Test_Cases.xlsx
 └── Postman_Screenshots/
```

### Note on Execution

Some API validations were performed using **documentation-based and mock responses** due to environment or network restrictions. This reflects real-world QA practices when live environments are unavailable.

---

## 🐞 Defect Management

Defects were logged in a structured format including:

* Bug ID
* Linked Test Case ID
* Summary and description
* Steps to reproduce
* Expected vs Actual result
* Severity and Priority

This demonstrates my understanding of **defect life cycle and reporting standards**.

---

## 🛠 Tools & Technologies

* Manual Testing
* Postman
* REST APIs
* Excel (Test documentation)
* Basic API validation concepts

---

## 🧠 Key Learnings

* End-to-end understanding of manual testing workflow
* Writing clear and maintainable test cases
* Identifying quality gaps and reporting defects effectively
* Understanding API behavior beyond UI interactions

---

## 🚀 Next Enhancements (Planned)

* Mini API automation using **Robot Framework**
* AI system testing (LLM / chatbot validation)
* Advanced API validation using Python

---

## 👤 About Me

I am a career-switching QA professional with a background in **Electronics, Hardware Engineering, and AI/ML projects**. I am actively transitioning into **Software Testing / QA / AI Tester roles**, combining structured testing practices with emerging AI systems validation.

---

📌 *This portfolio is created for learning, demonstration, and interview purposes.*
