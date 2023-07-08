# class 03



## Readings: FileIO & Exceptions


### Files on most modern file systems are composed of three main parts:
    - Header: metadata about the contents of the file (file name, size, type, and so on)
    - Data: contents of the file as written by the creator or editor
    - End of file (EOF): special character that indicates the end of the file


### File Paths
    - Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash / (Unix) or backslash \ (Windows)
    - File Name: the actual name of the file
    - Extension: the end of the file path pre-pended with a period (.) used to indicate the file type


### What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?

    - What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?
    -  it's important to ensure that they are properly closed after use to avoid any potential issues with data loss

### Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.
    - The read() method reads a specified number of bytes from the file, starting from the current file position
    - The readline() method, on the other hand, reads a single line of text from the file, starting from the current file position

###  Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.
    - In this construct, the 'try' block contains the code that may raise an exception
    - If an exception is raised, the control is transferred to the 'except' block, where the exception is handled. If no exception is raised, the 'except' block is skipped.
    - The 'finally' block contains code that is executed regardless of whether an exception was raised or not.                            


## Things I want to know more about
    - have a real example in try, exeption and finally 
    