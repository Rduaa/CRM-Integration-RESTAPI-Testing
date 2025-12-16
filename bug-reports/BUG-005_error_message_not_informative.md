# BUG-005

## Title
Validation errors return non-informative error message

## Environment
- API: CRM REST API
- Environment: Test

## Preconditions
- User is authenticated
- API endpoint is available

## Steps to Reproduce
1. Send request with invalid or incomplete payload
2. Check error response body

## Actual Result
API returns generic error message without field-level validation details

## Expected Result
API should return clear validation message with details for each invalid field

## Severity
Minor

## Priority
Low