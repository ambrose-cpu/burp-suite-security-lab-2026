# Burp Suite Web Application Security Testing Lab

## Project Overview
This project documents my hands-on practice with Burp Suite Community Edition on Kali Linux, using OWASP Juice Shop as an intentionally vulnerable web application.

The objective was to understand how web applications communicate through HTTP requests and responses and how security professionals inspect application traffic.

## Tools Used
- Kali Linux
- Burp Suite Community Edition
- OWASP Juice Shop
- Mozilla Firefox
- cURL

## Practical Activities

### 1. Proxy Configuration
- Configured Burp Suite proxy listener.
- Used localhost (127.0.0.1) on port 8080.
- Configured browser traffic inspection.

### 2. HTTP Traffic Analysis
- Intercepted HTTP requests.
- Identified GET and POST methods.
- Examined HTTP request and response headers.
- Explored HTTP status codes.

### 3. Burp Suite Repeater
- Sent captured requests to Repeater.
- Modified the User-Agent header.
- Resubmitted requests and examined server responses.

### 4. OWASP Juice Shop
- Set up a local Juice Shop environment.
- Created a test account.
- Investigated login requests.
- Examined authentication responses.
- Identified JWT authentication tokens.

## Key Concepts Learned
- HTTP request methods
- HTTP response codes
- Proxy servers
- HTTP headers
- Authentication
- JWT tokens
- Web application security testing

## Learning Outcome
This practical exercise improved my understanding of HTTP communication, proxy-based traffic inspection and basic web application security testing.

## Disclaimer
All practical exercises were conducted in a local, intentionally vulnerable training environment for educational purposes.
