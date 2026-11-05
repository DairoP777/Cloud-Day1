cURL Fundamentals — Week 1

1. What is cURL?

cURL is a command-line tool used to transfer data between a computer and a server. It allows us to communicate with websites and APIs directly through the terminal.

I used cURL to understand how HTTP requests work and how a server responds to them.

2. Exercise 1: HTTP GET Request

Command:

curl https://example.com -o example.html

What I learned:

curl runs the cURL command-line tool.

https://example.com is the website I'm requesting information from.

-o example.html saves the server's response into a local file called example.html.

Result:

The request retrieved the website's HTML content and saved it locally.

Key takeaway:

A GET request allows a client to request information from a server. This is one of the most common HTTP methods used when accessing websites and APIs.

3. Exercise 2: Inspecting HTTP Response Headers

Command:

curl -I https://example.com

What I learned:

The -I option requests the HTTP response headers without downloading the full page body.

My response included:

HTTP/2 200 — The server successfully processed the request.

Content-Type — Identifies the type of content being returned.

Server — Provides information about the server software.

Content-Length — Indicates the size of the response content, when provided.

Key takeaway:

HTTP headers provide useful information about how a server handles and responds to requests. They help developers and engineers troubleshoot communication between clients and servers.

4. What I Learned

Through these exercises, I learned:

How to send HTTP requests through the terminal.

The purpose of a GET request.

How to save a website's HTML response locally.

How to inspect HTTP response headers.

How to recognize a successful HTTP status code (200 OK).

5. Why This Matters for Cloud Engineering

Cloud engineers regularly work with web services, APIs, and remote servers.

Understanding HTTP requests and responses provides a foundation for troubleshooting connectivity issues, testing endpoints, and interacting with cloud-hosted applications.

6. Commands Reference

Command

Purpose

curl https://example.com -o example.html

Downloads and saves HTML

curl -I https://example.com

Displays HTTP response headers

Status: Week 1 — Completed cURL fundamentals exercises.
