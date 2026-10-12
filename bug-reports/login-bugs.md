# Login Bug Reports

## BUG-001 — Incorrect error message for empty username

### Environment
- Browser: Chrome
- Page: Login

### Preconditions
User is on the Login page.

### Steps to Reproduce
1. Open the Login page.
2. Leave the Username field empty.
3. Enter a valid password.
4. Click Login.

### Expected Result
The message "Username is required" is displayed.

### Actual Result
The message "Your username is invalid!" is displayed.

### Severity
Low

### Priority
Low

### Status
New
