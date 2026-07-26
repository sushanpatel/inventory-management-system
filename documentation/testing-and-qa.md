# Testing & Quality Assurance

## Overview

Testing and quality assurance were an important part of my work on the Inventory Management System.

As development progressed, I performed backend API testing, frontend testing, functional testing, bug identification, troubleshooting, and verification of application functionality.

Testing was used to identify issues across the application and help prepare the system for final project completion.

---

## Backend API Testing

I tested backend API endpoints to verify communication between application components and confirm that backend functionality was operating as expected.

Postman was used to execute and evaluate API requests during testing.

My API testing work included:

- Testing backend API endpoints
- Sending requests through Postman
- Reviewing API responses
- Identifying unexpected behaviour
- Troubleshooting API-related issues
- Verifying functionality after changes
- Reporting bugs and areas requiring improvement

This testing helped evaluate communication between the frontend, backend, and database components of the application.

---

## Frontend & Functional Testing

In addition to backend testing, I performed frontend and functional testing of the application.

Testing focused on verifying that application features behaved as expected from the user's perspective.

Areas evaluated included:

- User registration and login
- Authentication functionality
- Inventory management operations
- Inventory search and tracking
- Frontend-to-backend communication
- UPC/barcode functionality
- General application behaviour

---

## Test Cases

I created and executed test cases to evaluate application functionality.

The testing process involved:

1. Identifying the feature or functionality being tested
2. Defining the expected behaviour
3. Executing the test
4. Comparing the actual result with the expected result
5. Recording issues or unexpected behaviour
6. Retesting functionality after improvements or fixes

This provided a structured approach to evaluating the application rather than relying only on informal testing.

---

## Selected Test Results

The following are selected test cases from the final project testing documentation. These tests covered authentication, inventory management, staff management, warehouse functionality, and order workflows.

| Module | Test Scenario | Expected Result | Result |
|---|---|---|---|
| Registration | Valid email format and 8-character password | Registration successful | Pass |
| Registration | Empty email and password | Field validation displayed | Pass |
| Registration | Invalid email format and short password | Field validation displayed | Pass |
| Registration | Already registered email | Existing-email validation message displayed | Pass |
| Registration | Disposable email address | Disposable-email validation message displayed | Fail |
| Login | Valid email and password | Login successful | Pass |
| Login | Empty email and password | Field validation displayed | Pass |
| Login | Invalid email format and short password | Field validation displayed | Pass |
| Login | Email that does not exist | Error message displayed | Pass |
| Inventory | Add inventory with all required fields | Inventory added | Pass |
| Inventory | Add inventory with missing fields | Missing-field validation displayed | Pass |
| Inventory | Add positive quantity | Quantity added | Pass |
| Inventory | Add negative quantity | Validation message displayed | Fail — error page |
| Inventory | Remove positive quantity | Quantity removed | Pass |
| Inventory | Remove negative quantity | Validation message displayed | Fail — error page |
| Staff | Add staff with all required fields | Staff added | Pass |
| Staff | Add staff with missing fields | Missing-field validation displayed | Fail |
| Staff | Edit staff fields | Fields edited successfully | Pass |
| Staff | Delete staff | Staff deleted | Pass |
| Warehouse | Add warehouse with all required fields | Warehouse added | Pass |
| Warehouse | Edit warehouse fields | Warehouse edited | Pass |
| Warehouse | Link warehouse with product | Linking successful | Pass |
| Warehouse | Delete warehouse | Warehouse deleted | Pass |
| Warehouse | Delete warehouse containing linked products | Warehouse should not be deleted | Fail — warehouse was deleted |
| Order | Select order type | Order type selected | Pass |
| Order | Create order with required details | Order created | Pass |
| Order | Complete sale order | Product quantity decreases | Pass |
| Order | Complete purchase order | Product quantity increases | Pass |

### Findings

Testing confirmed that many of the application's primary workflows operated successfully while also identifying several validation and data-integrity issues.

Notable issues identified included:

- Disposable email addresses were not properly rejected during registration.
- Negative inventory quantity operations resulted in error pages rather than validation messages.
- Staff creation with missing required fields did not provide the expected validation.
- A warehouse containing linked products could be deleted when the expected behavior was to prevent deletion.

These failed test cases provided actionable areas for debugging and application improvement.

## Bug Identification & Reporting

During testing, I identified bugs and areas where the application could be improved.

Issues discovered during testing were documented and communicated so they could be investigated and addressed.

My work included:

- Bug identification
- Bug reporting
- Troubleshooting
- Improvement recommendations
- Verification after changes
- Final bug and improvement reporting

---

## Sprint Testing Work

During one project sprint, I focused on testing the backend API endpoints for the application.

The following sprint was planned around frontend testing.

During the final sprint, I completed backend and frontend testing and provided the team with a final bugs and improvements report.

This allowed testing to continue alongside development and provided a final evaluation of application functionality before project completion.

---

## Tools Used

### Postman

Postman was used for backend API testing and evaluating API requests and responses.

### Jira

Jira was used during the project for development and project-management activities.

### Git & GitHub

Git and GitHub supported version control and collaborative development throughout the project.

---

## Skills Demonstrated

The testing and QA work on this project provided hands-on experience with:

- API testing
- Postman
- Functional testing
- Frontend testing
- Backend testing
- Test case creation
- Bug identification
- Bug reporting
- Troubleshooting
- Software quality assurance
- Technical documentation
- Full-stack application testing

---

## Project Context

This testing work was completed as part of the Inventory Management System university software development project.

This document is included as a portfolio summary of my individual testing and quality assurance contributions to the project.
