# BUG-001

## Title
Auth endpoint accepts empty password

## Steps to Reproduce
1. Send POST `/auth/login`
2. Provide username with empty password
3. Send request

## Actual Result
Request is processed and token is returned

## Expected Result
API should return 400/401 validation error

## Severity
Major

## Priority
High