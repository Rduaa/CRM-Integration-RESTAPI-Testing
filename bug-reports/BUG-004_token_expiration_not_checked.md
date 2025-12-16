# BUG-004

## Title
Expired token is not rejected by protected endpoints

## Steps to Reproduce
1. Authenticate and get token
2. Use expired/invalid token in Authorization header
3. Call protected endpoint

## Actual Result
API returns 200 OK

## Expected Result
401 Unauthorized

## Severity
Critical

## Priority
High