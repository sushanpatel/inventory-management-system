# Bug & Improvement Report

## Overview

During development and testing of the Inventory Management System, I identified functional defects, validation issues, user-interface problems, and opportunities for application improvement.

My work included testing application workflows, documenting unexpected behavior, reporting bugs, troubleshooting issues, and verifying functionality throughout development.

This document highlights selected issues identified during the project and demonstrates my approach to software testing, problem identification, and quality improvement.

---

## Selected Bugs & Issues

### 1. Disposable Email Validation

**Area:** User Registration

**Issue:**  
The registration process did not properly reject disposable email addresses.

**Expected Behavior:**  
The application should display a validation message and prevent registration when a disposable email address is used.

**Observed Behavior:**  
The expected validation did not occur.

**Category:** Input Validation / Authentication

---

### 2. Negative Inventory Quantity

**Area:** Inventory Management

**Issue:**  
Inventory quantity operations allowed negative values to reach application processing without appropriate validation.

**Expected Behavior:**  
The application should reject invalid negative quantity input and display a validation message.

**Observed Behavior:**  
The operation resulted in an error page instead of the expected validation response.

**Category:** Input Validation / Error Handling

---

### 3. Staff Required-Field Validation

**Area:** Staff Management

**Issue:**  
Creating a staff record with required information missing did not produce the expected validation behavior.

**Expected Behavior:**  
Required fields should be validated before the staff record is submitted.

**Observed Behavior:**  
The expected missing-field validation was not displayed.

**Category:** Input Validation

---

### 4. Warehouse Deletion With Linked Products

**Area:** Warehouse Management

**Issue:**  
A warehouse containing linked products could be deleted.

**Expected Behavior:**  
The application should prevent deletion when products remain associated with the warehouse.

**Observed Behavior:**  
The warehouse was deleted despite existing product relationships.

**Category:** Data Integrity / Business Logic

---

## Additional Issues Identified

Testing and project review also identified additional areas requiring attention, including:

- Login and registration validation behavior
- Email validation
- Search and filtering functionality
- UPC/barcode-related errors
- Missing or inconsistent 404 error handling
- User-interface alignment and presentation issues
- Form validation behavior
- Application usability and workflow improvements

These findings were documented as part of the project's testing, bug reporting, and improvement process.

---

## Improvement Approach

When evaluating an issue, I focused on:

1. Identifying the affected application feature or workflow
2. Reproducing the unexpected behavior
3. Comparing the observed result with the expected result
4. Documenting the issue clearly
5. Evaluating the impact on functionality or user experience
6. Troubleshooting application components when appropriate
7. Retesting functionality after changes or improvements

This process helped connect development work with quality assurance and application troubleshooting.

---

## Skills Demonstrated

This work provided hands-on experience with:

- Software testing
- Functional testing
- Backend API testing
- Frontend testing
- Test case execution
- Bug identification and reporting
- Troubleshooting
- Input validation testing
- Error-handling analysis
- Data-integrity testing
- REST API testing
- Postman
- Jira
- Full-stack application debugging

---

## Project Context

The Inventory Management System originated as a collaborative university software development project. As development progressed, my responsibilities expanded across frontend and backend development, database implementation, authentication, API functionality, testing, debugging, and technical documentation.

The issues presented here are selected examples from the testing and project documentation and are included to demonstrate my software quality assurance and troubleshooting experience.
