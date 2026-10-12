# Login Test Cases

## TC-001 — Login with valid credentials

**Preconditions:** User is on the Login page.

**Steps:**
1. Enter a valid username.
2. Enter a valid password.
3. Click Login.

**Expected Result:** User is successfully logged in and redirected to the secure page.

**Priority:** High

---

## TC-002 — Login with invalid password

**Preconditions:** User is on the Login page.

**Steps:**
1. Enter a valid username.
2. Enter an invalid password.
3. Click Login.

**Expected Result:** User remains on the Login page and sees an error message.

**Priority:** High

---

## TC-003 — Login with empty username

**Preconditions:** User is on the Login page.

**Steps:**
1. Leave the Username field empty.
2. Enter a password.
3. Click Login.

**Expected Result:** An appropriate validation message is displayed.

**Priority:** Medium
