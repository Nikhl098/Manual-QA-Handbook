# 07. API, SQL, Web and Automation Basics

[Back to README](../README.md)

48 questions.

### Q1. What is an API?

Application Programming Interface: a way for software systems to talk to each other by sending requests and receiving responses.

### Q2. What is REST?

An architectural style for web APIs using standard HTTP methods on resources identified by URLs, usually exchanging JSON.

### Q3. What are the main HTTP methods?

GET reads data, POST creates data, PUT replaces data, PATCH partially updates data, DELETE removes data.

### Q4. What is the difference between PUT and PATCH?

PUT replaces the whole resource. PATCH changes only the fields you send.

### Q5. What is the difference between GET and POST?

GET retrieves data and puts parameters in the URL. POST sends data in the body to create or process something.

### Q6. What does status code 200 mean?

OK: the request succeeded.

### Q7. What does 201 mean?

Created: a new resource was created successfully.

### Q8. What does 204 mean?

No Content: the request succeeded and there is nothing to return.

### Q9. What does 400 mean?

Bad Request: the server could not understand the request because of invalid syntax or data.

### Q10. What does 401 mean?

Unauthorized: authentication is missing or invalid.

### Q11. What does 403 mean?

Forbidden: the user is authenticated but not allowed to access the resource.

### Q12. What does 404 mean?

Not Found: the resource does not exist.

### Q13. What does 500 mean?

Internal Server Error: something went wrong on the server.

### Q14. What do status code groups mean?

1xx informational, 2xx success, 3xx redirection, 4xx client error, 5xx server error.

### Q15. What is Postman?

A tool for building, sending and testing API requests, and for saving collections and writing assertions.

### Q16. What do you check when testing an API?

Status code, response body and schema, headers, response time, error handling, authentication, data validation and negative cases.

### Q17. What is JSON?

JavaScript Object Notation: a lightweight text format of key-value pairs and arrays used to exchange data.

### Q18. What is the difference between authentication and authorization?

Authentication proves who you are. Authorization decides what you are allowed to do.

### Q19. What is a Postman collection?

A group of saved requests that can be organized, shared and run together.

### Q20. What are Postman environment variables?

Named values (such as base URL or token) that let the same requests run against different environments.

### Q21. What is the difference between SOAP and REST?

SOAP is a strict protocol using XML with built-in standards. REST is a lighter style that usually uses JSON over HTTP.

### Q22. What is SQL?

Structured Query Language, used to read and manage data in relational databases.

### Q23. Why does a tester need SQL?

To verify data stored by the application, prepare test data and check that UI actions are saved correctly.

### Q24. What is the difference between DELETE, TRUNCATE and DROP?

DELETE removes selected rows and can be rolled back. TRUNCATE removes all rows quickly. DROP removes the whole table structure.

### Q25. What is a primary key?

A column (or set) that uniquely identifies each row and cannot be null.

### Q26. What is a foreign key?

A column that references the primary key of another table to link records.

### Q27. What is the difference between WHERE and HAVING?

WHERE filters rows before grouping. HAVING filters groups after GROUP BY.

### Q28. What are the main types of SQL JOIN?

INNER JOIN (matching rows only), LEFT JOIN (all left rows plus matches), RIGHT JOIN (all right rows plus matches), FULL JOIN (all rows from both).

### Q29. Write a query to get the second highest salary.

SELECT MAX(salary) FROM employees WHERE salary < (SELECT MAX(salary) FROM employees);

### Q30. How do you find duplicate rows in a table?

SELECT email, COUNT(*) FROM users GROUP BY email HAVING COUNT(*) > 1;

### Q31. What is the difference between a cookie and a session?

A cookie is stored in the browser. A session is stored on the server and usually referenced by a session ID cookie.

### Q32. What is browser cache and why does it matter in testing?

Stored copies of files that can show old content. Testers clear cache to be sure they see the latest version.

### Q33. What are browser developer tools used for in testing?

Inspecting HTML and CSS, watching network calls, reading console errors, checking storage and simulating devices.

### Q34. What is the difference between HTTP and HTTPS?

HTTPS encrypts traffic with TLS so data cannot easily be read or changed in transit.

### Q35. What is Selenium?

An open-source tool suite for automating web browsers for testing.

### Q36. What are the Selenium locators?

id, name, className, tagName, linkText, partialLinkText, CSS selector and XPath.

### Q37. What is XPath?

A query language to locate elements in an HTML document by path or attributes.

### Q38. What is the difference between absolute and relative XPath?

Absolute starts from the root with a full path (fragile). Relative starts anywhere with // and uses attributes (more stable).

### Q39. What is the difference between implicit and explicit wait in Selenium?

Implicit wait applies a global timeout to all element lookups. Explicit wait waits for a specific condition on a specific element.

### Q40. What is TestNG?

A Java testing framework that supports annotations, grouping, parallel runs, data providers and reports.

### Q41. What is the Page Object Model (POM)?

A design pattern where each page has a class holding its locators and actions, so test code is cleaner and easier to maintain.

### Q42. What is the difference between driver.close() and driver.quit()?

close() closes the current window. quit() closes all windows and ends the session.

### Q43. What is a Java array?

A fixed-size collection that stores elements of the same type, accessed by index starting at 0.

### Q44. What is the difference between an ArrayList and an array in Java?

An array has a fixed size. An ArrayList can grow and shrink dynamically.

### Q45. What are the four OOP principles?

Encapsulation, inheritance, polymorphism and abstraction.

### Q46. What is Git?

A version control system that tracks changes in files and allows collaboration.

### Q47. What are common Git commands?

git clone, git status, git add, git commit, git push, git pull, git branch and git merge.

### Q48. What is the difference between git pull and git fetch?

fetch downloads changes without merging. pull fetches and merges them into your current branch.

