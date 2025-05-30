# Postman API Testing Portfolio

Welcome to my API Testing Portfolio! 👋  
This project showcases my hands-on skills in creating, organizing, and automating API tests using **Postman**.

## 📌 About This Project

This collection includes tests written for a public demo API ([Reqres](https://reqres.in)) to demonstrate:

- Creating API test collections
- Writing test scripts using JavaScript in Postman
- Validating various HTTP methods (`GET`, `POST`, `PUT`, `DELETE`)
- Checking status codes, response structure, and authentication

## ✅ Test Coverage

### Collection: `Auth - Login`
- Validate status code on successful login
- Assert token is returned
- Handle incorrect/missing credentials

### Collection: `User Operations`
- `GET /users`: Validate user list and response time
- `GET /users/{id}`: Verify individual user data
- `POST /users`: Create a user and confirm creation
- `PUT /users/{id}`: Update user and check data
- `DELETE /users/{id}`: Confirm deletion

### Collection: `GET /ping`
- Verify API is up and running (health check)

## 🧪 Technologies & Tools Used
- [Postman](https://www.postman.com/)
- JavaScript for Postman test scripts
- JSON schema validation
- Git & GitHub for version control

## 📂 How to Use
1. Clone the repo:
   ```bash
   git clone https://github.com/tgo949/postman-api-tests-demo.git

