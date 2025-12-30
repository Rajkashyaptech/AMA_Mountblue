# AMA

## What is render in Django?
`render()` is a Django shortcut that loads a template, fills it with context data, and returns an HttpResponse.

## What is a command used to create project?
`django-admin startproject projectname` — creates a new Django project structure.

## Define static files?
Unchanging assets like CSS, JS, images served directly by the web server (not processed by Django).

## What is CSRF and how does Django prevent?
CSRF: Cross-Site Request Forgery — attack where malicious sites trick users into submitting unwanted requests.

Django prevents with CSRF tokens in forms; validates token on POST requests to ensure legitimacy.

## What is HTTPS?
HTTP Secure: encrypted version of HTTP using SSL/TLS for secure data transfer over the web.

## What is a status code in HTTP?
A 3-digit code in HTTP responses indicating the result (e.g., 200 OK, 404 Not Found, 500 Internal Server Error).

## What is GET and POST request?
GET: Requests data from server (safe, idempotent, parameters in URL).

POST: Sends data to server to create/update (not idempotent, data in request body).

## What is a URL?
Uniform Resource Locator: address of a resource on the web (e.g., https://example.com/path).

## What is Django admin panel?
Built-in web interface for managing database models (CRUD operations) without writing custom views.

## What is URL routing in Django?
Mapping URLs to views using `urlpatterns` in `urls.py`; determines which view handles a request.

## What are Django forms?
Classes for handling HTML forms: validate user input, render HTML, and process form submissions.
