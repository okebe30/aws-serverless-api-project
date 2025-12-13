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

### Lambda Function Test (Python)
Execution réussie de la fonction Lambda retournant une réponse JSON.
![Lambda Function Test](screenshots/lambda-test.png)

### API Gateway Route
Route GET `/hello` configurée et intégrée avec AWS Lambda.
![API Gateway Route](screenshots/api-gateway-route.png)

### API Gateway Stage
Stage `$default` avec auto-deployment activé.
![API Gateway Stage](screenshots/api-gateway-stage.png)

### API Response in Browser
Test de l’API depuis le navigateur confirmant la réponse JSON.
![API Response in Browser](screenshots/browser-test.png)
