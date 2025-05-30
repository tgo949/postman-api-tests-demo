# postman-api-tests-demo
Demo Postman API Test Collection for Reqres and custom endpoints
This repository showcases a sample Postman collection designed to demonstrate my API testing skills as part of my QA portfolio. It includes functional tests written using Postman's built-in scripting language and tests against publicly available APIs such as [Reqres](https://reqres.in).

---

## 📌 Collection Overview

- **Tool**: Postman
- **Assertions**: Written in JavaScript
- **Environment**: No environment required (self-contained)
- **Use Case**: Demonstrating skills in writing test scripts, using collection runners, and verifying REST APIs

---

## ✅ Included Tests

These tests are created under a collection named `Reqres API Tests`:

1. **Status Code Validation**  
   Confirms that the API returns the expected `200 OK` response.

2. **Response Time Check**  
   Ensures the API responds in under 500ms.

3. **Content-Type Header Validation**  
   Checks if the response is in JSON format.

4. **Response Body Field Check**  
   Verifies that specific keys and values are present in the JSON response.

5. **Token Authentication Test**  
   Simulates login and ensures a token is returned.

6. **API Key Handling**  
   Demonstrates usage of `x-api-key` in the header when required.

7. **Error Handling / Negative Testing**  
   Validates how the API behaves when wrong or missing data is passed.

---

## 📂 Folder Structure

```bash
.
├── Reqres.postman_collection.json  # The exported Postman collection
├── README.md                       # This file
