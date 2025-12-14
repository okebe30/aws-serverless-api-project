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
