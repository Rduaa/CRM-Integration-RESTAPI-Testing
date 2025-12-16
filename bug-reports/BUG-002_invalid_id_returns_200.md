# BUG-002

## Title
GET user by invalid id returns 200 OK

## Steps to Reproduce
1. Send GET `/users/0` (or `/users/-1`)
2. Check response

## Actual Result
200 OK with empty object

## Expected Result
404 Not Found or validation error

## Severity
Major

## Priority
Medium