# Class 27

## Django Models

[Link ---> Class27](./Class27.md)

#### Explain the purpose and basic structure of Django models. How do they help in creating and managing database schema in a Django application?
    - They represent the logical structure and behavior of data within a Django application and serve as the interface to interact with the underlying database

    - The basic structure of a Django model is typically defined in a Python class that inherits from the django.db.models.Model base class


#### Describe the primary features and functionality of the Django Admin interface. How can it be customized to suit the specific needs of a project?
    - The Admin interface is a powerful tool provided by Django that automatically generates a user-friendly interface for managing the data in your application's models.

    -  Automatic CRUD operations: The Django Admin interface provides a complete set of Create, Read, Update, and Delete (CRUD) operations for each registered model.

    -  Model listing and filtering: The Admin interface displays a list view of all registered models, allowing you to see the records in a tabular format   

    - Customization options: The Django Admin interface is highly customizable to suit the specific needs of your project.



#### Briefly outline the key components and workflow of a Django application, as discussed in the Beginner’s Guide to Django. How do these components interact with each other to create a functional web application?
    - Models: Models represent the data structure and behavior of your application.

    -Views: Views handle the logic of your application and define how data is presented to the user

    -  Templates: Templates determine the presentation and layout of your application's user interface.

    - URLs: URLs map incoming requests from the user's browser to the corresponding views in your application