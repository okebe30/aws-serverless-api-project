# AWS Serverless API Project

This project demonstrates the design and implementation of a **serverless REST API** using AWS managed services.  
It showcases how to build, deploy, and validate a backend API without managing servers.

---

## Overview

The API uses **AWS Lambda** for backend logic and **Amazon API Gateway (HTTP API)** to expose an endpoint.  
This architecture is scalable, cost-efficient, and follows cloud best practices.

---

## Architecture

- **AWS Lambda (Python)** — Backend compute
- **Amazon API Gateway (HTTP API)** — Request routing
- **IAM Role** — Secure execution permissions

---

## Features

- Fully serverless architecture (no server management)
- REST API with a GET endpoint
- JSON-based responses
- Automatic deployment via API Gateway
- Scalable and cost-efficient design
- Clear separation of compute, routing, and security

---

## API Endpoint

**GET `/hello`**



## Screenshots

### Lambda Function Test
Successful execution of the AWS Lambda function returning a JSON response.

![Lambda Function Test](screenshots/lambda-test.png)

---

### API Gateway Route
HTTP API route configured to integrate Amazon API Gateway with the Lambda function.

![API Gateway Route](screenshots/api-gateway-route.png)

---

### API Response in Browser
Validation of the API response directly from a web browser.

![API Response in Browser](screenshots/browser-test.png)

---

> **Note:**  
> The live AWS endpoint was created during development and may no longer be active.  
> The screenshots above confirm successful deployment and execution.
