# ReqRes API - Test Cases

## TC001 - Get list of users

**Endpoint:** `/api/users?page=2`  
**Method:** GET  
**Expected Status Code:** 200  

**Expected Result:**
- The API should return a list of users.
- The response body should contain page information and user data.

**Status:** Passed

---

## TC002 - Get single user

**Endpoint:** `/api/users/2`  
**Method:** GET  
**Expected Status Code:** 200  

**Expected Result:**
- The API should return data for a single user.
- The response body should contain user ID, email, first name, last name and avatar.

**Status:** Passed

---

## TC003 - Create user

**Endpoint:** `/api/users/2`  
**Method:** POST  
**Expected Status Code:** 201  


**Request Body:**

```
{
  "name": "Eduardo Lisboa",
  "job": "QA Tester"
}
```

Expected Result:

The API should create a new user.
The response body should return the name, job, ID and creation date.

Status: Passed

## TC004 - Update user

**Endpoint:** `/api/users/2`  
**Method:** PUT  
**Expected Status Code:** 200  

**Request Body:**

```
{
  "name": "Eduardo Lisboa",
  "job": "QA Analyst"
}
```

**Expected Result:**

The API should update the full user information.
The response body should return the updated name, job and update date.

**Status:** Passed

## TC005 - Partially update user

**Endpoint:** `/api/users/2`  
**Method:** PATCH  
**Expected Status Code:** 200  

**Request Body:**

```
{
  "job": "Junior QA Tester"
}
```

**Expected Result:**

The API should partially update the user information.
The response body should return the updated job and update date.

**Status:** Passed

## TC006 - Delete user

**Endpoint:** `/api/users/2`  
**Method:** DELETE  
**Expected Status Code:** 204  



**Expected Result:**

The API should delete the selected user.
The response body should be empty.

**Status:** Passed
