# Test Case Template

Copy this table for each test case, or use the CSV version: [test-case-template.csv](test-case-template.csv).

| Field | Value |
|---|---|
| Test Case ID | TC_LOGIN_001 |
| Module / Feature | Login |
| Title | Verify login with valid credentials |
| Requirement ID | REQ-001 |
| Priority | High |
| Type | Functional / Positive |
| Preconditions | User account exists and is active |
| Test Data | username: demo_user, password: (valid password) |
| Steps | 1. Open the login page<br>2. Enter username<br>3. Enter password<br>4. Click Login |
| Expected Result | User lands on the dashboard and sees their name |
| Actual Result | (fill after execution) |
| Status | Pass / Fail / Blocked / Not Run |
| Environment | Chrome 120, Windows 11, QA build 1.4.2 |
| Executed By / Date | (name, date) |
| Remarks | Link to bug ID if failed |

## Writing tips

- One test case checks one thing.
- Write the expected result as something you can see, not "works fine".
- Do not depend on another test case having run first.
- Cover positive, negative and boundary cases.
