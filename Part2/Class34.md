# API Deployment

# Class-34

###  [Link](./Class34.md)

#### What are the key principles to follow when organizing and configuring Django settings for a project, according to the “Django Settings Best Practices” reading?

    - Use Environment Variables: Store sensitive or environment-specific settings, like secret keys or database credentials

    - Environment-based settings: Use different settings files for different environments 

    - Separation of Concerns: Divide your settings into separate files for better organization and maintainability

    - settings can be divided into three files: base.py, development.py, and production.py.

    - Add Configuration Parameters: Instead of hardcoding values directly in settings files, use configuration parameters and constants to make the code more flexible and maintainable

    - Use Constants for Settings: Use uppercase names for settings variables to distinguish them as constants




####  How does the White Noise library contribute to the efficient serving of static files in a Django application, and what are the steps to integrate it into a project?


    - WhiteNoise is a Python library that enhances the serving of static files in Django applications, making it more efficient and suitable for production use. It acts as a lightweight WSGI middleware that serves static files directly from memory

    - This results in better performance and reduces the complexity of deploying Django applications, especially for small to medium-scale projects.

    -  WhiteNoise loads static files into memory during the application's startup, and then serves them directly from memory

    -  WhiteNoise automatically handles static file collection and storage during the deployment process. This makes it easier to deploy Django applications without needing additional server configurations



#### What is the purpose of Cross-Origin Resource Sharing (CORS) in web applications, and how can it be implemented and configured in a Django project to control access to resources?

    - is a security feature implemented by web browsers to control access to resources (such as APIs or static files) on a web server from a different domain or origin.
    
    -  It is a fundamental security mechanism to prevent unauthorized cross-origin requests, which can be potentially harmful, such as cross-site request forgery (CSRF) or theft of sensitive data.

    -  CORS allows a web server to specify which domains are allowed to access its resources and which HTTP methods

    - By default, CORS headers are applied to all URLs in your Django application. 