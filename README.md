# API Security Risk Analysis

## Project Overview
This project demonstrates a basic API security analysis using a public test API. 
The objective was to identify common security issues such as unauthenticated endpoints, 
data exposure, and authorization weaknesses.

## Tools Used
- Google Chrome Developer Tools
- Postman
- Public Test API (JSONPlaceholder)

## API Endpoints Tested
- /users
- /users/1
- /users/2
- /posts
- /comments

## Testing Methodology
1. Accessed API endpoints using browser and Postman.
2. Inspected network requests using Chrome Developer Tools.
3. Analyzed API responses for sensitive information.
4. Identified potential security risks.
5. Documented findings and recommendations.

## Key Security Findings
- Unauthenticated endpoint access
- Excessive data exposure
- Potential object-level authorization weakness
- Public access to content endpoints
- Email exposure in comments

## Recommendations
- Implement authentication for sensitive endpoints
- Limit exposure of unnecessary data fields
- Enforce strict authorization checks
- Mask or restrict sensitive information

## Report
The detailed security analysis is available in the **API_Security_Risk_Analysis_Report.pdf** file in this repository.

## Author
Shradha Dubey
