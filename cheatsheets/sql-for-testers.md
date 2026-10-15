# SQL for Testers Cheat Sheet

```sql
-- all rows
SELECT * FROM users;

-- filter and sort
SELECT name, email FROM users WHERE status = 'active' ORDER BY name;

-- count
SELECT COUNT(*) FROM orders WHERE order_date >= '2026-01-01';

-- group
SELECT status, COUNT(*) FROM orders GROUP BY status;

-- groups with a condition
SELECT customer_id, COUNT(*) AS total
FROM orders GROUP BY customer_id HAVING COUNT(*) > 5;

-- find duplicates
SELECT email, COUNT(*) FROM users GROUP BY email HAVING COUNT(*) > 1;

-- join
SELECT o.id, u.name
FROM orders o INNER JOIN users u ON u.id = o.user_id;

-- second highest salary
SELECT MAX(salary) FROM employees WHERE salary < (SELECT MAX(salary) FROM employees);

-- insert, update, delete (use carefully, always with WHERE for update and delete)
INSERT INTO users (name, email) VALUES ('Test User', 'test@example.com');
UPDATE users SET status = 'inactive' WHERE id = 10;
DELETE FROM users WHERE id = 10;
```
