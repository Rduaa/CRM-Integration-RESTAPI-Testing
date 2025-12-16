# BUG-003

## Title
Create contact allows missing required fields

## Steps to Reproduce
1. Send POST `/users/add` (or create endpoint)
2. Provide payload without required fields (e.g., name/email)
3. Send request

## Actual Result
Contact is created successfully

## Expected Result
400 Bad Request with validation details

## Severity
Major

## Priority
Medium