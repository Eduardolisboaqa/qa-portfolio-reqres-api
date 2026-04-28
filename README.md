# ReqRes API Testing Project

## Project Overview

This project demonstrates API testing using Postman with the ReqRes API.

The objective was to validate different HTTP methods, response status codes, response body structure and basic API behavior.

## API Tested

ReqRes API

## Tools Used

- Postman
- GitHub
- ReqRes API

## Test Scope

The following scenarios were tested:

- Get list of users
- Get single user
- Create user
- Update user
- Partially update user
- Delete user

## HTTP Methods Tested

- GET
- POST
- PUT
- PATCH
- DELETE

## Test Cases

| ID | Scenario | Method | Expected Status | Status |
|----|----------|--------|----------------|--------|
| TC001 | Get list of users | GET | 200 OK | Passed |
| TC002 | Get single user | GET | 200 OK | Passed |
| TC003 | Create user | POST | 201 Created | Passed |
| TC004 | Update user | PUT | 200 OK | Passed |
| TC005 | Partially update user | PATCH | 200 OK | Passed |
| TC006 | Delete user | DELETE | 204 No Content | Passed |

## Validations Performed

The following validations were performed during the test execution:

- HTTP status code validation
- Response body validation
- User data validation
- Created user response validation
- Updated user response validation
- Empty response validation for DELETE request

## Repository Structure

```text
qa-portfolio-reqres-api/
│
├── README.md
├── postman-collection/
├── test-cases/
├── bug-reports/
├── evidence/
└── test-summary/
```

## Evidence

Screenshots of the test executions are available in the `/evidence` folder.

## Postman Collection

The exported Postman collection is available in the `/postman-collection` folder.

## Test Summary

The final test execution summary is available in the `/test-summary` folder.

## Bug Reports

No bugs were identified during the test execution. The bug report section is included to demonstrate the documentation structure.

## Conclusion

This project helped me practice API testing fundamentals, including HTTP methods, endpoint validation, status code verification, response body analysis and technical documentation.
