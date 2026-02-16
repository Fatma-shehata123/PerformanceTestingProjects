# Todo Application Performance Testing

## 📖 Overview
This project focuses on **Performance and API Testing** for a Todo Application using **Apache JMeter**.
It simulates real user behavior including authentication, task management, and data validation.

## 🛠 Tools & Technologies
- Apache JMeter 5.6.3
- REST API Testing
- HTTP Header Manager
- JSON Extractor
- Response Assertions

## 🧪 Test Flow

### 🔹 User Registration & Authentication
- Visit Sign Up Page
- Register Request
- Generate random user data
- Extract Access Token dynamically

### 🔹 Get Tasks API
- Retrieve Todo list
- Validate response status code
- Verify response body

### 🔹 Add Todo API
- Add new Todo item
- Validate successful creation
- Assert response data

## 📂 Test Components
- HTTP Header Manager for authorization
- Status Code Assertions
- Body Assertions
- Random data generation
- Token extraction for authenticated requests

## 📊 Reports & Results
- View Results Tree for request validation
- CSV results file for execution data
- HTML Dashboard Report available in `report/index.html`

## 🎯 Objectives
- Validate API functionality under load
- Measure response time and throughput
- Ensure authentication and authorization stability

## 👩‍💻 Author
Fatma Shehata
