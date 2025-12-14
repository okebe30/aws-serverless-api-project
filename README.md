# AWS Serverless API Project

This project demonstrates the design and implementation of a **serverless REST API** using AWS managed services.  
It showcases how to build, deploy, and validate a backend API without managing servers.

---

## Overview

The API uses **AWS Lambda** for backend logic and **Amazon API Gateway (HTTP API)** to expose a public endpoint.  
This architecture provides scalability, security, and cost efficiency while minimizing operational overhead.

---

## Architecture

- **AWS Lambda (Python)**  
  Handles request processing and returns JSON responses.

- **Amazon API Gateway (HTTP API)**  
  Routes HTTP requests to the Lambda function.

- **IAM Role**  
  Grants secure execution permissions to Lambda.

---

## Key Features

- Fully serverless architecture (no server management)
- REST API with a GET endpoint
- JSON-based responses
- Automatic deployment via API Gateway
- Scalable and cost-efficient design
- Clear separation of compute, routing, and security

---

## API Endpoint

**GET /hello**

### Sample Response
```json
{
  "message": "Serverless API is working!",
  "status": "success"
}
---

## Screenshots

### Lambda Function Test
Successful execution of the AWS Lambda function returning a JSON response.

![Lambda Function Test](screenshots/lambda-test.png)

---

### API Gateway Route
HTTP API route configured to integrate API Gateway with the Lambda function.

![API Gateway Route](screenshots/api-gateway-route.png)

---

### API Response in Browser
Validation of the API response directly from a web browser.

![API Response in Browser](screenshots/browser-test.png)

---

## Note
The live AWS endpoint was created during development and may no longer be active.  
The screenshots above confirm successful deployment and execution.

---

## Author

**Oumar Kebe**  
Cloud Engineer
