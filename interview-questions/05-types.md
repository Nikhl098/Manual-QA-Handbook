# 05. Types of Testing

[Back to README](../README.md)

45 questions.

### Q1. What is functional testing?

Testing what the system does against the requirements, such as login, search and payment features.

### Q2. What is non-functional testing?

Testing how the system behaves: performance, security, usability, compatibility and reliability.

### Q3. What is smoke testing?

A quick check of the most important functions on a new build to decide if it is stable enough for deeper testing.

### Q4. What is sanity testing?

A narrow check after a small change or bug fix to confirm that the specific area works.

### Q5. What is the difference between smoke and sanity testing?

Smoke is broad and shallow on a new build. Sanity is narrow and deep on a specific change. Smoke decides if testing can start, sanity decides if a fix is reasonable.

### Q6. What is integration testing?

Testing the interaction between modules or systems to find interface issues.

### Q7. What is unit testing?

Testing the smallest part of code, like a function, usually done by developers.

### Q8. What is system testing?

Testing the complete integrated application against requirements.

### Q9. What is acceptance testing?

Testing to confirm the product is ready for delivery and meets business requirements.

### Q10. What are top-down and bottom-up integration?

Top-down tests from the main modules downward using stubs. Bottom-up tests lower modules first using drivers.

### Q11. What is a stub?

A dummy module that stands in for a lower-level module that is not ready.

### Q12. What is a driver?

A dummy program that calls a module under test when the calling module is not ready.

### Q13. What is big bang integration testing?

Integrating all modules at once and testing together. Hard to locate faults.

### Q14. What is end-to-end testing?

Testing a complete user flow through all systems, such as browse, add to cart, pay, and receive confirmation email.

### Q15. What is performance testing?

Checking speed, responsiveness and stability under a given load.

### Q16. What is load testing?

Testing behavior under expected and peak user load.

### Q17. What is stress testing?

Pushing the system beyond its limits to see how and when it breaks and recovers.

### Q18. What is spike testing?

Testing behavior when the load suddenly jumps up or down.

### Q19. What is endurance (soak) testing?

Running under normal load for a long time to find memory leaks and slowdowns.

### Q20. What is scalability testing?

Checking how well the system handles growth when resources or load are increased.

### Q21. What is volume testing?

Testing with a large amount of data to check performance and data handling.

### Q22. What is security testing?

Checking for vulnerabilities and verifying authentication, authorization, data protection and input handling.

### Q23. What is SQL injection?

An attack where malicious SQL is inserted into an input field to manipulate the database. Prevented with parameterized queries and validation.

### Q24. What is XSS (cross-site scripting)?

An attack where malicious script is injected into a page and executes in other users' browsers.

### Q25. What is usability testing?

Evaluating how easy and pleasant the product is to use for real users.

### Q26. What is compatibility testing?

Checking that the software works across browsers, operating systems, devices and screen sizes.

### Q27. What is cross-browser testing?

Testing the application on different browsers and versions to confirm consistent behavior and layout.

### Q28. What is localization testing?

Checking the software for a specific language and region: text, date, currency and cultural fit.

### Q29. What is accessibility testing?

Checking that people with disabilities can use the product, for example with screen readers and keyboard-only navigation.

### Q30. What is recovery testing?

Checking how well the system recovers after crashes, failures or power loss.

### Q31. What is installation testing?

Verifying install, upgrade and uninstall work correctly.

### Q32. What is configuration testing?

Testing the software with different hardware and software configurations.

### Q33. What is monkey testing?

Giving random inputs without a plan to see if the application crashes.

### Q34. What is gorilla testing?

Repeatedly testing one module heavily to make sure it is robust.

### Q35. What is the difference between ad hoc and exploratory testing?

Both are unscripted. Ad hoc is random and informal. Exploratory is structured by a charter, with learning and notes.

### Q36. What is A/B testing?

Showing two versions to different users and measuring which performs better against a goal.

### Q37. What is mobile app testing?

Testing apps on devices for functionality, interruptions (calls, notifications), battery, network changes, gestures and different OS versions.

### Q38. What is database testing?

Verifying data integrity, schema, CRUD operations, constraints, triggers and stored procedures.

### Q39. What is data migration testing?

Verifying that data moved from an old system to a new one is complete and correct.

### Q40. What is automation testing?

Using tools and scripts to run tests automatically, best for repetitive, stable and regression tests.

### Q41. What should you automate?

Repetitive tests, regression and smoke suites, data-driven tests and stable features. Avoid automating one-off, rapidly changing or purely exploratory tests.

### Q42. What are the pros and cons of automation?

Pros: speed, repeatability, coverage. Cons: setup and maintenance cost, cannot judge look and feel, scripts break when UI changes.

### Q43. What is the difference between manual and automation testing?

Manual is done by a person without scripts, flexible and good for exploration. Automation uses tools for fast, repeatable execution.

### Q44. How do you maintain a regression suite?

Regularly reviewing and updating regression tests to remove obsolete ones, add new features and keep them reliable.

### Q45. What is a flaky test?

A test that sometimes passes and sometimes fails with no code change, often due to timing, data or environment issues.

