# AWS Serverless API Project

This project demonstrates the design and implementation of a **serverless REST API** using AWS managed services.  
It showcases how to build, deploy, and validate a backend API **without managing servers**, following cloud best practices.

---

## Overview

The API is implemented using **AWS Lambda** for backend logic and **Amazon API Gateway (HTTP API)** to expose a public endpoint.  
This architecture provides scalability, low operational overhead, and cost efficiency.

The project is designed as a **portfolio-ready example** of serverless backend development on AWS.

---

## Architecture

The solution is composed of the following AWS services:

- **AWS Lambda (Python)**  
  Executes backend logic and returns JSON responses.

- **Amazon API Gateway (HTTP API)**  
  Exposes the REST endpoint and routes requests to Lambda.

- **IAM Role**  
  Provides secure execution permissions for the Lambda function.

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
