# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a modern REST API using the FastAPI framework, including routing, request/response handling, and basic validation.

**Skills practiced:** API design, HTTP methods, JSON handling, request validation, and using third-party Python libraries

## 📝 Tasks

### 🛠️ Create a FastAPI REST API

#### Description
Build a REST API using FastAPI that supports creating, reading, updating, and deleting resources (CRUD). Use in-memory storage (e.g., a list or dictionary) to keep the project simple.

#### Requirements
Completed project should:

- Define API endpoints for CRUD operations (GET, POST, PUT/PATCH, DELETE)
- Use Pydantic models for request validation and response schemas
- Return appropriate HTTP status codes (e.g., 200, 201, 404)
- Include at least one endpoint that accepts query parameters
- Provide clear responses in JSON format
- Include instructions for running the API server (e.g., `uvicorn main:app --reload`)