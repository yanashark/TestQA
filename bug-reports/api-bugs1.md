# API Bug Reports

## BUG-002 — API accepts empty required fields

### API
POST /users

### Preconditions
API is available.

### Request Body
{
  "name": "",
  "username": "",
  "email": ""
}

### Steps to Reproduce
1. Open Postman.
2. Select POST request.
3. Enter the endpoint /users.
4. Send a request with empty required fields.
5. Check the response.

### Expected Result
API should reject the request and return HTTP 400 Bad Request.

### Actual Result
API returns HTTP 201 Created and creates a new user.

### Severity
High

### Priority
High

### Status
New
