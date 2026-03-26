# Restful Booker API Testing Project

##  Project Overview

This project demonstrates API testing of the Restful Booker application using Postman. It includes functional, negative, and integration testing of booking APIs.

## Tools Used

* Postman (API Testing)

![alt text](<Screenshot 2026-03-26 121827.png>)

* Newman (CLI Runner)
* GitHub (Version Control)

## API Tested

https://restful-booker.herokuapp.com/apidoc/

## Project Structure

* `restful-booker-collection.json` → Postman Collection
* `environment.json` → Environment variables
* `test-cases.xlsx` → Manual test cases

## Test Scenarios Covered

* Authentication (Generate Token)
* Create Booking
* Get Booking
* Update Booking
* Delete Booking
* Integration Testing (End-to-End Flow)

## Integration Flow

1. Generate Token
2. Create Booking
3. Get Booking
4. Update Booking
5. Delete Booking

## Key Validations

* Status Codes validation
* Response body validation
* Data consistency
* Authentication handling

##  How to Run

1. Import collection in Postman
2. Set environment variables
3. Run using Collection Runner

## Author

Niroj Thapa
