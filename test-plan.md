# Test Plan — CRM Integration REST API

## 1. Goal
Validate stability and correctness of CRM REST API integration flows: authentication, contacts/users data, and basic CRUD operations.

## 2. In Scope
- Auth (login, token handling)
- Contacts/Users retrieval
- Create/update data (where available)
- Negative cases (invalid payload, invalid id, unauthorized)

## 3. Out of Scope
- UI testing
- Load/performance testing
- Security pentesting

## 4. Test Types
- Smoke API testing
- Functional API testing
- Regression sanity checks

## 5. Test Data
- Valid user credentials (demo)
- Invalid credentials
- Valid/invalid IDs

## 6. Entry / Exit Criteria
Entry: API available, base URL known  
Exit: Smoke passed, no critical defects open