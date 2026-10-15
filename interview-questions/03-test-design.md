# 03. Test Design Techniques

[Back to README](../README.md)

33 questions.

### Q1. What is black box testing?

Testing based on requirements and behavior without looking at the internal code.

### Q2. What is white box testing?

Testing with knowledge of the code structure, checking statements, branches and paths.

### Q3. What is grey box testing?

A mix of both: limited knowledge of internals, such as database or architecture, is used while testing from the outside.

### Q4. What is boundary value analysis (BVA)?

A technique that tests values at the edges of input ranges, because bugs often occur there. For range 1-100 test 0, 1, 2, 99, 100, 101.

### Q5. What is equivalence partitioning?

Dividing inputs into groups that should behave the same and testing one value from each group. For age 18-60: below 18, 18-60, above 60.

### Q6. What is decision table testing?

A technique that lists combinations of conditions and the expected action for each, good for complex business rules.

### Q7. What is state transition testing?

Testing how the system moves between states based on events, such as a login that locks after 3 failed attempts.

### Q8. What is use case testing?

Deriving test cases from the steps in user use cases, including the main flow and alternate flows.

### Q9. What is error guessing?

Using experience to guess where bugs likely hide, for example empty fields, special characters or very long input.

### Q10. What is exploratory testing?

Simultaneous learning, test design and execution without predefined scripts, guided by a charter and the tester's judgment.

### Q11. What is ad hoc testing?

Informal, unplanned testing to find defects, with no documentation or specific technique.

### Q12. What is pairwise (all-pairs) testing?

A technique that covers every pair of input values in few test cases, instead of all full combinations.

### Q13. What is statement coverage?

The percentage of code statements executed by tests.

### Q14. What is branch (decision) coverage?

The percentage of decision outcomes (true and false of each if) executed by tests.

### Q15. What is path coverage?

The percentage of possible execution paths through the code that tests exercise.

### Q16. What is positive testing?

Testing with valid input to confirm the system works as expected.

### Q17. What is negative testing?

Testing with invalid or unexpected input to confirm the system handles it gracefully, for example showing an error message.

### Q18. What are the parts of a good test case?

ID, title, preconditions, steps, test data, expected result, actual result, status, priority and remarks.

### Q19. How do you write a good test case?

Keep it clear and short, one purpose per case, independent from others, repeatable, with exact expected results and traceability to a requirement.

### Q20. What is a test charter?

A short mission statement for an exploratory session, such as "Explore the checkout with invalid coupons".

### Q21. What is session-based testing?

Exploratory testing done in timeboxed sessions with a charter and notes afterward.

### Q22. What is risk-based testing?

Prioritizing tests based on the likelihood and impact of failure, so high-risk areas are tested first and deepest.

### Q23. How do you prioritize test cases?

By business criticality, risk, usage frequency, defect history and dependencies.

### Q24. What is test estimation?

Predicting the effort and time testing will take, using methods like past experience, work breakdown or three-point estimation.

### Q25. What are test design techniques categories?

Specification-based (black box), structure-based (white box) and experience-based techniques.

### Q26. How would you test a login page?

Valid login, invalid password, empty fields, wrong username, case sensitivity, password masking, show password toggle, forgot password, lockout after attempts, SQL injection input, session timeout, remember me, browser back after logout and UI on different browsers.

### Q27. How would you test a pen?

Check writing, ink flow, grip, cap fit, ink color, durability, drop test, temperature, leak, refill, price and appearance.

### Q28. How would you test a lift (elevator)?

Door open/close, floor buttons, weight limit, emergency button, alarm, speed, display, power failure behavior, door sensors and fan/light.

### Q29. How would you test an ATM?

Card insert, PIN validation, wrong PIN limit, balance, withdrawal limits, insufficient funds, receipt, cash dispense, timeout, cancel and network failure.

### Q30. How would you test a search box?

Valid and invalid terms, empty search, special characters, long text, partial match, case, spelling mistakes, no results message, speed, and suggestions.

### Q31. How would you test a file upload feature?

Allowed and disallowed types, size limit, empty file, duplicate names, special characters in name, cancel upload, slow network, multiple files and virus or malicious file handling.

### Q32. How would you test a signup form?

Mandatory fields, email format, password rules, confirm password match, duplicate email, field length, terms checkbox, verification email and success redirect.

### Q33. How would you test a shopping cart?

Add, remove, update quantity, price and tax totals, coupon code, out of stock items, cart persistence after login, and checkout flow.

