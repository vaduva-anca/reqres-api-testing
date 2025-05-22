# Reqres API Testing Project

This repository contains a complete API testing project based on the public Reqres.in API, created using Postman and JavaScript test scripts.

## 🔧 Tech Stack
- Postman
- JavaScript (test scripts)
- JSON Schema
- Newman (CLI runner)

## ✅ Test Coverage
- **CRUD Operations**:
  - `POST`: Create user & registration
  - `GET`: List users, view user details, resources
  - `PUT`: Update user
  - `DELETE`: Delete user

- **Assertions**:
  - HTTP status codes
  - JSON schema validation
  - Field formats: email, avatar URL, HEX color
  - Negative test scenarios: missing fields, 404s, invalid credentials

- **Performance Testing**:
  - Simulated slow API response using `?delay=3`
  - `pm.response.responseTime` validation

## 🚀 Automation Ready
This collection is fully compatible with Newman:
```bash
newman run "Reqres API Testing Project.postman_collection.json" -r html
```

## 📄 Author
Created as a QA portfolio project to demonstrate practical API testing skills.

