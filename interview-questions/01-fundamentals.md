# 01. Testing Fundamentals

[Back to README](../README.md)

40 questions.

### Q1. What is software testing?

The process of checking that software works as expected and finding defects before users do. It compares actual behavior with expected behavior.

### Q2. Why is testing necessary?

Bugs found late cost more to fix and can harm users or the business. Testing reduces risk and builds confidence in quality.

### Q3. What is the difference between QA and QC?

QA is process-focused and prevents defects (standards, reviews, audits). QC is product-focused and detects defects (executing tests).

### Q4. What is the difference between QA and testing?

Testing is one activity inside QA. QA covers the whole process of building quality in, testing checks the product itself.

### Q5. What is a bug or defect?

A flaw where the software behaves differently from the expected requirement.

### Q6. What is an error, a defect and a failure?

An error is a human mistake. It can introduce a defect in the code. When that defect is hit at runtime, the visible wrong behavior is a failure.

### Q7. What is verification?

Checking that we are building the product right, through reviews, walkthroughs and inspections, without running the code.

### Q8. What is validation?

Checking that we built the right product, by running the software and confirming it meets user needs.

### Q9. What is the difference between verification and validation?

Verification is static (documents, code review) and asks "are we building it right?". Validation is dynamic (executing the app) and asks "are we building the right thing?".

### Q10. What is a test case?

A set of steps, input data, preconditions and expected result used to verify one specific behavior.

### Q11. What is a test scenario?

A high-level statement of what to test, for example "Verify login". One scenario usually produces many test cases.

### Q12. What is a test plan?

A document describing scope, approach, resources, schedule, risks and entry/exit criteria for testing.

### Q13. What is a test strategy?

A high-level, often organization-wide document describing the general testing approach. A test plan is project specific and follows the strategy.

### Q14. What is test data?

The input data prepared to execute test cases, including valid, invalid and boundary values.

### Q15. What is a test environment?

The hardware, software, network and configuration where tests run, set up to resemble production.

### Q16. What is a test suite?

A collection of test cases grouped for a purpose, such as a regression suite or smoke suite.

### Q17. What is a test bed?

The environment plus the setup (hardware, OS, tools, data) needed to run tests.

### Q18. What is a test script?

Usually automated code that executes a test case. Sometimes also used for a written manual procedure.

### Q19. What is a test log?

A chronological record of test execution: what ran, who ran it, when and the result.

### Q20. What is a test closure report?

A summary produced at the end of testing: what was tested, pass/fail counts, open defects, lessons learned and sign-off.

### Q21. What is the Requirement Traceability Matrix (RTM)?

A table that maps requirements to test cases so you can prove every requirement is covered.

### Q22. What is test coverage?

A measure of how much of the requirements or code is exercised by tests, usually as a percentage.

### Q23. What are entry criteria?

Conditions that must be true before a test phase starts, such as build deployed, test cases reviewed and environment ready.

### Q24. What are exit criteria?

Conditions that let you stop testing, such as all critical tests executed, no open critical bugs, and pass rate target met.

### Q25. What is the difference between a test case and a test scenario?

A scenario is a one-line idea of what to test. A test case is the detailed, step-by-step instance with data and expected results.

### Q26. What is the pesticide paradox?

If you keep running the same tests, they stop finding new bugs. You must review and update test cases regularly.

### Q27. What are the seven principles of testing?

Testing shows presence of defects, exhaustive testing is impossible, early testing, defect clustering, pesticide paradox, testing is context dependent, absence-of-errors fallacy.

### Q28. What is defect clustering?

A small number of modules usually contain most of the defects (the 80/20 idea).

### Q29. What is the absence-of-errors fallacy?

Finding and fixing many bugs does not help if the product does not meet the users' needs.

### Q30. Why is exhaustive testing impossible?

There are too many input and path combinations. We use risk and prioritization to choose what to test.

### Q31. What is static testing?

Examining work products (requirements, design, code) without executing the software, for example reviews and inspections.

### Q32. What is dynamic testing?

Testing by running the software with inputs and checking outputs.

### Q33. What is the difference between a review, walkthrough and inspection?

A review is a general check by peers. A walkthrough is led by the author to explain the work. An inspection is the most formal, with defined roles and metrics.

### Q34. What is a test oracle?

The source used to decide the expected result, such as requirements, a previous version or a domain expert.

### Q35. What is retesting?

Running the same test again after a defect fix to confirm the bug is gone.

### Q36. What is regression testing?

Re-running existing tests after a change to confirm nothing else broke.

### Q37. What is the difference between retesting and regression testing?

Retesting verifies a specific fixed bug. Regression checks that the change did not break other working features.

### Q38. What is a tester's main goal?

To give accurate information about quality and risk so the team can decide, by finding defects early and clearly reporting them.

### Q39. What qualities make a good tester?

Curiosity, attention to detail, clear communication, domain understanding, analytical thinking and a user mindset.

### Q40. What is quality?

Fitness for use: the product meets requirements and user expectations reliably.

