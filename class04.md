# class04 -Reading

### What are the key differences between classes and objects in Python, and how are they used to create and manage instances of a class?
    - In Python, a class is a template for creating objects, while an object is an instance of a class

#### heres an example :
    - class Person:
    def info(self, name, age):
        self.name = name
        self.age = age

    def say_hello(self):
        print(f"Hello, my name is {self.name} and I'm {self.age} years old.")


        #### and thats how to create an object 
        person1 = Person("Ali", 25)



#### Explain the concept of recursion and provide an example of how it can be used to solve a problem in Python. What are some best practices to follow when implementing a recursive function?
    - Recursion is a programming technique where a function calls itself repeatedly until a base case is reached
    - Define a base case: Make sure that there is a base case that will eventually be reached, which will stop the recursive calls and return a value
    - Avoid unnecessary recursion: Avoid unnecessary recursion, as it can lead to excessive function call overhead and slower execution times



#### What is the purpose of pytest fixtures and code coverage in testing Python code? Explain how they can be used together to improve the quality and maintainability of a project.
    - Pytest fixtures and code coverage can be used together to improve the quality and maintainability
    - pytest fixtures and code coverage are powerful tools for testing and improving the quality of Python code
    - developers can ensure that their code is thoroughly tested, efficient, and maintainable.


## Things I want to know more about 
    - OBJECT ORIENTED PROGRAMING 