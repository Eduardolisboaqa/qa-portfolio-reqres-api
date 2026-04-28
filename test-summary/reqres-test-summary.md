# ReqRes API - Test Summary

## Project Overview

This project was created to practice API testing using Postman and the ReqRes API.

The main objective was to validate HTTP methods, response status codes, response body structure and basic API behavior.

## Scope

The following scenarios were tested:

- Get list of users
- Get single user
- Create user
- Update user
- Partially update user
- Delete user

## Tools Used

- Postman
- ReqRes API
- GitHub

## HTTP Methods Tested

- GET
- POST
- PUT
- PATCH
- DELETE

## Test Results

| Test Case | Description | Method | Expected Status Code | Status |
|----------|-------------|--------|----------------------|--------|
| TC001 | Get list of users | GET | 200 | Passed |
| TC002 | Get single user | GET | 200 | Passed |
| TC003 | Create user | POST | 201 | Passed |
| TC004 | Update user | PUT | 200 | Passed |
| TC005 | Partially update user | PATCH | 200 | Passed |
| TC006 | Delete user | DELETE | 204 | Passed |

## Bug Summary

No bugs were identified during the test execution.

## Conclusion

The tested scenarios behaved according to the expected results.

This project helped reinforce API testing fundamentals, including HTTP methods, endpoint validation, status code verification, response body analysis and test documentation.
