# Adjutor API QA Assessment

This repository contains automated API test scripts created for the Lendsqr Adjutor API Quality Assurance Assessment.

## Modules Tested

### Validation NG
## Bank Verification Number
- Initialize BVN Consent
- Complete Consent and Get BVN Details
## Get Accounts for a BVN
- Initialize BVN Accounts Consent
- Complete Consent and Get BVN Accounts

### Credit Bureaus NG
- Get Credit Report from CRC Credit Bureau
- Get Credit Report from First Central Credit Bureau

### Decisioning
- Get Decision Models
- Get Decision Models Details


## Test Coverage

The automated test scripts include:
- HTTP status code validation
- Response validation
- Authentication validation
- Response time validation

## Authentication

Bearer Token authentication was used for all endpoints.

Authorization format:

Authorization: Bearer <API_KEY>

## Tools Used
- Postman
- GitHub

## How To Run

1. Import the Postman collection JSON file
2. Import the Postman environment JSON file
3. Add your API key to the environment variable
4. Run requests individually or through Collection Runner

## Repository Contents

- Postman Collection
- Postman Environment
- Automated API Test Scripts

## Notes

Actual API responses observed during testing were documented and compared against the official API documentation. Some live responses differed from the documented sample responses during execution.
