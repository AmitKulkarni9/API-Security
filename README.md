# API-Security

# Introduction

When an API is accessed by method say for e.g. Get/Post it will give some response containing response data, response code along-with response headers.

The OWASP Secure Headers Project describes these HTTP response headers that applications can use to increase the security of the application. Once set, these HTTP response headers can restrict modern browsers from running into easily preventable vulnerabilities. The OWASP Secure Headers Project intends to raise awareness and use of these headers. Below are the Response Headers described by OWASP which increases the security of the application.

# Response Headers
  <p>HTTP Strict Transport Security (HSTS)</p>
  <p>X-Frame-Options</p>
  <p>X-Content-Type-Options</p>
  <p>Content-Security-Policy</p>
  <p>X-Permitted-Cross-Domain-Policies</p>
  <p>Referrer-Policy</p>
  <p>Feature-Policy</p>
  <p>Public Key Pinning Extension for HTTP (HPKP)</p>
  <p>Expect-CT</p>
  <p>X-XSS-Protection</p>


# Solution
This is a Python based API-Security framework containing ApiSecurityHeader.py script which will check the above mentioned Security response headers are present and contains the required value.
The script will work for ANY API provided. It supports both get and post method.

# Reference
https://github.com/OWASP/www-project-secure-headers
