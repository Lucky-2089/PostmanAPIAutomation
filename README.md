# API Test Automation with Postman and Jenkins

This project automates API testing using Postman and Jenkins. The collection includes tests for microservices, and the execution is automated using Newman and Jenkins.

## Contents

- **Postman Collection**: The API tests are stored in `postman/Microservices.json`.
- **Environment**: The API environment settings are in `postman/Development.json`.
- **Jenkinsfile**: The Jenkins pipeline configuration for running the API tests.

## Usage

1. Clone the repository.
2. Run the API tests using Newman:
   ```bash
   newman run postman/Microservices.json --environment postman/Development.json
