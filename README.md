# API-Security

Introduction

When an API is called by method say for e.g. Get/Post it will give some response containing response data, response code along-with response headers.

The OWASP Secure Headers Project describes these HTTP response headers that applications can use to increase the security of the application. Once set, these HTTP response headers can restrict modern browsers from running into easily preventable vulnerabilities. The OWASP Secure Headers Project intends to raise awareness and use of these headers. Below are the Response Headers described by OWASP which increases the security of the application.

Solution
Python script ApiSecurityHeader.py will check the required Security response headers are present and contains the required value.
The script will work for any API provided. It supports both get and post method.

Reference
https://github.com/OWASP/www-project-secure-headers
