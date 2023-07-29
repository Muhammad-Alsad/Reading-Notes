# Class 33

## Authentication & Production Server

[Link](./Class33.md)

#### What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?

    - serve as a secure and compact way to transmit information between parties as a JSON object. They are primarily used for authentication and authorization in web applications

    - JWTs consist of three parts separated by dots: header, payload, and signature

    - The primary purpose of JWTs is to securely represent claims between two parties, typically an application (client) and a server


#### How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?


    - JWT Authentication can be integrated with Django REST Framework (DRF) to secure API endpoints by adding authentication and authorization mechanisms based on JSON Web Tokens. The key components involved in this process are:
        - Django REST Framework 
        - Django settings.py Configuration
        - rest_framework_simplejwt Library
        - Sending JWT Tokens with Requests


#### Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?

    - Performance
    - Security
    - Stability
    - Static File Serving


    * For deploying a Django application in production :- 
        - Gunicorn 

        - uWSGI
        
        - Daphne