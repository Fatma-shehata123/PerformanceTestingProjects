# BlazeDemo Performance Testing

## 📖 Overview
This project performs **Performance Testing** on the BlazeDemo flight booking system using **Apache JMeter**.
It covers multiple testing strategies including **Load Testing**, **Stress Testing**, and **Soak Testing** to evaluate system stability and scalability.

## 🛠 Tools & Technologies
- Apache JMeter 5.6.3
- HTTP Request Sampler
- HTTP Header Manager
- Response Assertions
- Summary Report
- Aggregate Report

## 🧪 Test Structure

### 🔹 Load Testing Group
Simulates normal expected traffic to verify system performance under typical load.
- Reserve Flight Request
- Purchase Flight Request
- Confirmation Request

### 🔹 Stress Testing Group
Pushes the system beyond normal load to identify breaking points.
- Same booking flow under high load
- Monitors response time and error rate

### 🔹 Soak Testing Group
Runs the system under sustained load for a period of time.
- Detects memory leaks
- Checks long-term stability

## 📊 Reports
The following listeners are used for analysis:
- Summary Report
- Aggregate Report
- View Results Tree

An **HTML Dashboard Report** is available in the `report` folder.
To view it:
1. Open `report/index.html`
2. View metrics such as response time, throughput, and error percentage

## 🎯 Objectives
- Evaluate system performance under different loads
- Identify bottlenecks and failure points
- Ensure system reliability and stability

## 👩‍💻 Author
Fatma Shehata
