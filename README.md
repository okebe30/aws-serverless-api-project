# AWS Serverless API Project

This project demonstrates a serverless REST API built using AWS managed services. It shows how to deploy and validate a backend API without managing servers, using AWS Lambda and Amazon API Gateway.

## Architecture
- AWS Lambda (Python) for backend logic  
- Amazon API Gateway (HTTP API) to expose the endpoint  
- IAM Role for secure execution permissions  

## Features
- Serverless architecture  
- REST API with a GET endpoint  
- JSON response format  
- Automatic deployment via API Gateway  
- Scalable and cost-efficient design  

## API Endpoint
GET /hello

Sample response:
```json
{
  "message": "Serverless API is working!",
  "status": "success"
}
> **Note:**  
> The live AWS endpoint was created during development and may no longer be active.  
> The screenshots below confirm successful deployment and execution.

## Screenshots

### Lambda Function Test
Successful execution of the AWS Lambda function returning a JSON response.  
![Lambda Function Test](screenshots/lambda-test.png)

### API Gateway Route
HTTP API route configured to integrate API Gateway with the Lambda function.  
![API Gateway Route](screenshots/api-gateway-route.png)

### API Response in Browser
Validation of the API response directly from a web browser.  
![API Response in Browser](screenshots/browser-test.png)

## Author

**Oumar Kebe**  
Cloud Engineer
