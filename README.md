# AWS Serverless API Project

This project demonstrates a simple serverless REST API built using AWS services.

## Architecture
- AWS Lambda (Python)
- Amazon API Gateway (HTTP API)
- IAM Role for Lambda execution

## Features
- Serverless API endpoint
- GET route returning JSON response
- Deployed using API Gateway with automatic deployment

## API Endpoint
GET /hello

Example:
https://581ia3uupd.execute-api.us-east-1.amazonaws.com/hello

# AWS Serverless API Project

This project demonstrates a simple serverless REST API built using AWS services.

## Architecture
- AWS Lambda (Python)
- Amazon API Gateway (HTTP API)
- IAM Role for Lambda execution

## Features
- Serverless API endpoint
- GET route returning JSON response
- Automatic deployment using API Gateway



## Screenshots

### Lambda Function (Python)
Test execution of the AWS Lambda function returning a JSON response.
![Lambda Function Test](screenshots/lambda-test.png)

### API Gateway Route
API Gateway route configuration linking the GET /hello endpoint to the Lambda function.
![API Gateway Route](screenshots/api-gateway-route.png)

### API Response in Browser
Test of the API from the browser confirming the JSON response.
![API Response in Browser](screenshots/browser-test.png)
