# BUG-005

## Title
Validation errors return non-informative message

## Steps to Reproduce
1. Send request with invalid payload
2. Check error response body

## Actual Result
Generic error without field details

## Expected Result
Clear message with field-level validation info

## Severity
Minor

## Priority
Low