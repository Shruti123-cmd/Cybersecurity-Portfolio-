# 🔐 PortSwigger Lab – Burp Suite Username Enumeration

## 📌 Overview
This lab was completed on PortSwigger Web Security Academy to understand how Burp Suite can be used for intercepting HTTP requests and identifying authentication vulnerabilities such as username enumeration.

---

## 🧠 Objective
To analyze login functionality and identify valid usernames by observing differences in server responses using Burp Suite.

---

## 🛠 Tools Used
- Burp Suite Community Edition
- Web Browser (with proxy enabled)
- PortSwigger Web Security Academy Lab Environment

---

## 🔎 Process

### 1. Intercepting Requests
- Captured login requests using Burp Suite Proxy
- Observed parameters like `username` and `password`

---

### 2. Request Analysis
- Modified login credentials manually
- Sent requests using Burp Repeater
- Compared server responses for different inputs

---

### 3. Response-Based Enumeration
- Noticed differences in server behavior based on username input
- Used HTTP response codes and behavior changes to identify valid username

---

### 4. Exploitation
- Found a valid username from intercepted traffic analysis
- Used password: `trustno1`
- Successfully logged in and completed the lab

---

## 🔐 Security Concept Learned
- Username Enumeration
- Authentication weaknesses
- Information disclosure via response differences
- HTTP status code-based analysis

---

## 🚀 Result
Successfully identified a valid username and bypassed authentication using Burp Suite by analyzing HTTP request/response behavior.

---

## 📚 Conclusion
This lab improved my understanding of how attackers can exploit weak authentication systems and how Burp Suite is used in real-world web application security testing.
