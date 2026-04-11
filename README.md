# Cross-Device Regression Testing

## Overview
This project contains regression test cases executed across multiple devices to validate that core application functionality remains stable after changes or updates.

The focus is on ensuring consistent behavior across environments and identifying defects introduced during development.

---

## Objective
- Verify existing features continue to work after updates
- Ensure consistent functionality across devices and platforms
- Identify defects and inconsistencies in behavior

---

## Testing Scope
- Functional regression testing
- Cross-device compatibility validation
- UI and workflow consistency
- Error handling and validation checks

---

## Testing Environments
- Desktop (Windows)
- Mobile devices (iOS / Android)
- Web browsers (Chrome, Edge)

---

## Test Coverage
- User input validation (email, password, required fields)
- Form submission behavior
- API request validation (where applicable)
- Navigation and user flows
- HTTP method validation (GET, POST, PUT, DELETE)
- Content-type validation

---

## Sample Test Scenarios

| Test Case ID | Scenario | Expected Result |
|-------------|--------|----------------|
| TC_01 | Valid email and password | User successfully created |
| TC_02 | Invalid email format | Error message displayed |
| TC_03 | Weak password | Validation error returned |
| TC_04 | Duplicate user | System rejects duplicate entry |
| TC_05 | Incorrect HTTP method | Method not allowed response |

---

## Tools Used
- Manual testing
- Excel (test case management)

---

## Test Results Summary
- Majority of valid scenarios passed successfully
- Invalid input cases correctly triggered validation errors
- Several edge cases failed, indicating potential gaps in validation logic

---

## Key Findings
- Some inconsistencies observed across devices
- Certain invalid inputs were not properly handled
- Regression testing helped identify validation and logic gaps

---

## Files
- cross_device_regression_test_cases.xlsx

---

## Notes
This project demonstrates structured regression testing across multiple environments, emphasizing real-world QA practices such as validation, edge case handling, and cross-device consistency.# cross-device-regression-testing. During cross-device regression testing, both successful and failure scenarios were identified. Some failure cases were intentionally included to demonstrate how defects are captured and documented in real QA workflows.
