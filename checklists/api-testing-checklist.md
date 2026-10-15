# API Testing Checklist

- [ ] Correct status codes for success and error cases (200, 201, 204, 400, 401, 403, 404, 500)
- [ ] Response body has the right fields, data types and values
- [ ] Required fields missing returns a clear error
- [ ] Invalid data types and out of range values are rejected
- [ ] Authentication: no token, wrong token and expired token
- [ ] Authorization: a user cannot access another user's data
- [ ] Headers (Content-Type, caching, CORS) are correct
- [ ] Response time is acceptable
- [ ] Create, read, update and delete work end to end
- [ ] Pagination, filtering and sorting parameters work
- [ ] Idempotency: repeating the same PUT or DELETE gives a safe result
- [ ] Error messages do not leak sensitive information
