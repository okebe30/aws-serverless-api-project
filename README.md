# AWS Serverless API Project

This project demonstrates the design and implementation of a **serverless REST API** using AWS managed services.  
It highlights how to build, deploy, and validate a backend API without managing servers.

---

## Overview

The API is built using **AWS Lambda** to handle backend logic and **Amazon API Gateway** to expose an HTTP endpoint.  
This approach ensures scalability, low operational overhead, and cost efficiency.

---

## Architecture

- **AWS Lambda (Python)**  
  Handles request processing and returns JSON responses.

- **Amazon API Gateway (HTTP API)**  
  Exposes the REST endpoint and routes requests to Lambda.

- **IAM Role**  
  Grants Lambda the required execution permissions securely.

---

## Key Features

- Serverless architecture (no server management)
- REST API with a GET endpoint
- JSON-based response
- Automatic deployment via API Gateway
- Scalable and cost-efficient design

---

## API Endpoint


**Sample Response**
```json
{
  "message": "Serverless API is working!",
  "status": "success"
}

## Screenshots

### Lambda Function Test
![Lambda Test](screenshots/lambda-test.png)

### API Gateway Route
![API Gateway Route](screenshots/api-gateway-route.png)

### API Response in Browser
![Browser Test](screenshots/browser-test.png)

## Author
Oumar Kebe
 — Cloud Engineer
