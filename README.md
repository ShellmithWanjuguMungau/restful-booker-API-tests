# Restful Booker API Testing

## Overview
Manual and Automated API testing performed on:
https://restful-booker.herokuapp.com

## Scope
- Authentication Testing
- Booking CRUD Operations
- Error Scenario Testing

## Tools Used
- Postman
- GitHub

## Files Included
- Postman Collection (JSON)
- Test Cases and Bug report pdf
- Screenshots

## Automation Scripts

Basic Postman test scripts were added to validate:

- Status codes

Example:

pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});

## Summary
All major functionalities were tested including authentication, booking creation, update, deletion, and validation scenarios.
Automated scripts also added as bonus.


## Future improvements
in the furture my automation scripts will include:

- Response time
- Response structure
- Authentication token presence
- Data validation



