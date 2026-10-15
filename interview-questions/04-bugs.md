# 04. Defects and Bug Reporting

[Back to README](../README.md)

34 questions.

### Q1. What is a bug life cycle?

The states a defect goes through from discovery to closure: New, Assigned, Open, Fixed, Retest, Verified, Closed. It may also be Reopened, Rejected, Deferred or Duplicate.

### Q2. What is a defect report?

A document describing a defect with enough detail for a developer to reproduce and fix it.

### Q3. What should a good bug report contain?

Title, ID, environment, build version, steps to reproduce, expected result, actual result, severity, priority, screenshot or video, logs and reporter.

### Q4. What is severity?

How much the defect hurts the system functionality. It is usually set by the tester.

### Q5. What is priority?

How soon the defect should be fixed. It is usually set by the product owner or manager based on business need.

### Q6. What is the difference between severity and priority?

Severity is technical impact, priority is urgency of the fix. Example: a typo in the company name on the home page is low severity but high priority.

### Q7. Give an example of high severity and low priority.

The app crashes only on a very old browser that almost no one uses.

### Q8. Give an example of high priority and low severity.

A wrong logo or brand spelling on the home page before a launch.

### Q9. Give an example of high severity and high priority.

The payment fails for every customer at checkout.

### Q10. Give an example of low severity and low priority.

A minor alignment issue on a rarely visited help page.

### Q11. What are the severity levels?

Commonly Critical (system down or data loss), High (major feature broken), Medium (feature partly broken with workaround) and Low (cosmetic).

### Q12. What is a blocker bug?

A defect that stops testing or use of the system entirely, so work cannot continue until it is fixed.

### Q13. What is a reopened bug?

A bug marked fixed that still reproduces after retesting, so it goes back to the developer.

### Q14. What is a rejected bug?

A reported defect the developer or owner decides is not a bug, for example working as designed.

### Q15. What is a deferred bug?

A valid bug that will be fixed in a later release.

### Q16. What is a duplicate bug?

A bug that was already reported earlier by someone else.

### Q17. What is a non-reproducible bug?

A defect that the developer cannot recreate. Provide more steps, data, environment details and logs.

### Q18. What do you do if a developer says "it is not a bug"?

Re-check the requirement, show evidence (steps, screenshots), discuss politely and if still disputed involve the product owner or BA to decide.

### Q19. What do you do if you cannot reproduce a bug?

Retry with the same environment and data, check build version, look at logs, note frequency and share a video, then talk with the reporter.

### Q20. What is defect density?

The number of defects divided by the size of the software, such as defects per 1000 lines of code or per module.

### Q21. What is defect leakage?

Defects that escaped testing and were found in production or by users.

### Q22. What is defect removal efficiency (DRE)?

Defects found before release divided by total defects (before plus after release), as a percentage.

### Q23. What is defect age?

The time between when a defect was reported and when it was fixed or closed.

### Q24. What is root cause analysis (RCA)?

Investigating why a defect happened so the cause, not just the symptom, can be fixed and prevented.

### Q25. What is a showstopper defect?

A critical defect that prevents release of the software.

### Q26. What is a workaround?

A temporary way to avoid a bug until it is properly fixed.

### Q27. What is a false positive in testing?

A test reports a failure but there is no real defect (for example, a flaky test or environment issue).

### Q28. What is a false negative in testing?

A test passes although a real defect exists.

### Q29. What is defect triage?

A meeting where the team reviews new defects and decides their severity, priority, owner and timeline.

### Q30. What is a good bug title?

Short and specific, stating what is wrong and where. For example: "Checkout: Place Order button unresponsive when coupon applied".

### Q31. What is a test defect versus a production defect?

A test defect is found internally before release. A production defect is found by users after release and usually costs more.

### Q32. How do you report a bug that happens intermittently?

State that it is intermittent with the approximate frequency, attach logs and video, list conditions when it happened and the environment.

### Q33. What tools are used for defect tracking?

Jira, Bugzilla, Azure DevOps, Mantis, Redmine and similar tools.

### Q34. What is the cost of a defect over time?

It rises sharply the later it is found: a requirement bug found in production costs far more than the same issue caught in review.

