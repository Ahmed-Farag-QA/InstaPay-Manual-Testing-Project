# Test Plan - InstaPay Manual Testing Project

## 1. Introduction
This Test Plan defines the scope, approach, resources, and schedule for testing the InstaPay application. The goal is to ensure the quality, reliability, and correctness of the core financial transactions and user workflows.

---

## 2. Scope

### In Scope:
- User Registration
- OTP Verification
- Login
- Link Bank Account
- Balance Inquiry
- Send Money
- Request Money
- Beneficiaries Management
- Transaction History
- Notifications
- Logout

### Out of Scope:
- API Testing
- Database Testing
- Performance Testing
- Security Testing
- Automation Testing

---

## 3. Test Approach

The testing will be performed using:

- Black Box Testing
- Functional Testing
- End-to-End Testing
- Negative Testing
- Validation Testing

Testing will focus on user-centric workflows and business-critical scenarios.

---

## 4. Test Levels

- System Testing (Primary Level)

---

## 5. Test Design Techniques

- Equivalence Partitioning
- Boundary Value Analysis
- Error Guessing

---

## 6. Entry Criteria

- Requirements are defined and approved
- Application build is stable and accessible
- Test data is available
- Test environment is ready

---

## 7. Exit Criteria

- All planned test cases are executed
- No Critical or High severity defects are open
- All defects are documented and tracked
- Test Summary Report is completed

---

## 8. Assumptions

- Users have valid mobile numbers for registration
- OTP service is functional
- Stable internet connection is available
- Application behaves consistently in production-like environment

---

## 9. Risks

- OTP delivery delays or failures
- Application downtime or instability
- Limited ability to reproduce production issues
- Data restrictions on real financial flows

---

## 10. Deliverables

- Test Plan
- Test Scenarios
- Test Cases
- Bug Reports
- RTM (Requirements Traceability Matrix)
- Test Summary Report

---

## 11. Tools

- Jira (Bug Tracking)
- Excel / Google Sheets (Test Cases)
- Postman (Future API reference - out of scope for this project)
- GitHub (Documentation Storage)
