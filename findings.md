# Lab Findings

## Finding 1: HTTP Request Interception
Successfully intercepted HTTP requests using Burp Suite.

## Finding 2: HTTP Method Identification
Identified GET and POST requests and understood their different purposes.

## Finding 3: HTTP Header Modification
Modified the User-Agent header using Burp Repeater and observed the server response.

## Finding 4: Authentication Testing
Captured a login request and examined authentication responses.

## Finding 5: JWT Authentication
Observed an authentication token returned in the login response.

## Observation
The Juice Shop login response did not expose a traditional Set-Cookie header in the response examined.

Further investigation of JWT security and session management is planned.
