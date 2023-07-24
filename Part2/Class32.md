# Class 32
## Permissions & Postgresql

[Link](./Class32.md)


#### What are the key components and purpose of Django Rest Framework (DRF) permissions, and how do they help in securing an API?
    - Django Rest Framework (DRF) provides a powerful and flexible permissions system to help secure APIs built using Django
        - Permission classes
        - Authentication
        - Authorization checks
        -Custom permissions


#### In SQL, what is the purpose of the SELECT statement, and how would you use it to retrieve all columns from a table called ‘employees’?
    - To retrieve all columns from a table called 'employees,' you can use the SELECT statement

    - SELECT *
        FROM employees;


#### Can you explain the role of DRF Generic Views and provide examples of their usage in building a RESTful API?        

    - The role of DRF Generic Views is to simplify the creation of API views by providing generic implementations for common actions on resources. They are especially useful when you want to follow RESTful principles and provide consistent endpoints for your resources.
     - ListAPIView
     - CreateAPIView
     - RetrieveAPIView
     - UpdateAPIView
     - DestroyAPIView