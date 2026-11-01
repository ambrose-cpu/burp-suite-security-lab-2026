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
  ## Screenshots and Evidence

### 1. Burp Suite Interface
![Burp Suite Interface](screenshots/Screenshot%20From%202026-10-31%2018-04-56.png)

This screenshot demonstrates the Burp Suite interface used
for intercepting and analyzing web application traffic.

### 2. HTTP Request Analysis
![HTTP Request Analysis](screenshots/Screenshot%20From%202026-10-31%2018-13-28.png)

This screenshot demonstrates the inspection of HTTP requests
during web application security testing.

### 3. Web Traffic Inspection
![Web Traffic Inspection](screenshots/Screenshot%20From%202026-10-31%2018-27-44.png)

This screenshot documents HTTP traffic inspection.

### 4. Security Testing Evidence
![Security Testing](screenshots/Screenshot%20From%202026-10-31%2019-13-37.png)

This screenshot provides additional evidence from the
Burp Suite practical exercises.
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
