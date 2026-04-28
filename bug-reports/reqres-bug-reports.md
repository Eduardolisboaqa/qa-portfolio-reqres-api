# ReqRes API - Bug Reports

## No critical bugs found

During the API testing execution, no critical bugs were identified.

The API responses behaved according to the expected results for the tested scenarios, including:

- Listing users
- Retrieving a single user
- Creating a user
- Updating a user
- Partially updating a user
- Deleting a user

This section is included to demonstrate bug documentation structure.

---

## Bug Report Example

**Bug ID:** BUG001  
**Title:** Response body does not persist created user data  
**Severity:** Low  
**Priority:** Low  
**Environment:** Postman  
**API:** ReqRes API  
**Endpoint:** `/api/users`  
**Method:** POST  

### Steps to Reproduce

1. Send a POST request to `/api/users`.
2. Use the following request body:

```json
{
  "name": "Eduardo Lisboa",
  "job": "QA Tester"
}
```
3. Verify the response body.
4. Try to retrieve the created user using the returned ID.

**Expected Result**

The created user should be available for future GET requests using the returned ID.

**Actual Result**

The API returns a successful creation response, but the created user is not actually persisted.

**Status**

Open

**Note**

This behavior is expected for ReqRes because it is a public test API. This bug report is included as a documentation example for portfolio purposes.
