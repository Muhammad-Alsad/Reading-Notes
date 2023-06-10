# Class 16

## Serverless Functions

#### What are the key characteristics of serverless computing, and how does it differ from traditional server-based architectures?



   - No server management: In a serverless architecture, the cloud provider takes care of server management, including provisioning, scaling, and maintenance. Developers are relieved from the operational overhead of managing servers.

 -    Event-driven execution: Serverless functions are triggered by specific events or requests, such as an HTTP request, a database update, a file upload, or a message from a queue. When an event occurs, the cloud provider automatically runs the corresponding function.

   - Pay-per-use pricing: Serverless computing follows a pay-per-use pricing model. You are billed only for the actual execution time of your functions, with no charges for idle time. This makes it cost-effective for applications with sporadic or unpredictable workloads.

 -    Pay-per-use pricing: Serverless computing follows a pay-per-use pricing model. You are billed only for the actual execution time of your functions, with no charges for idle time. This makes it cost-effective for applications with sporadic or unpredictable workloads.

   - Stateless functions: Serverless functions are designed to be stateless, meaning they don't store any persistent state between invocations. Any required state is usually stored in external services like databases or object storage.



#### How can one get started with Vercel, and what are the main steps involved in deploying a serverless function using Vercel?
    - sign up a vercel account and connect git provider

    - Create and deploy a project

    - Configuring Your Project : You can specify the framework you are using, the build command, and other deployment settings.

    Assigning a Custom Domain - You can find it right below your Project's name on the Project list:

    Applying Updates via Git

    Deploy serverless functions: To deploy a serverless function, create a directory within your project for the functions. Inside that directory, create a file for your function, such as api.js or hello.js. Write your function code in this file.Deploy the serverless function: Run the vercel command again to deploy the changes, including your serverless function. Vercel will build and deploy the updated project, including the function


#### What are APIs, and how can they be utilized in Python applications to access and manipulate data from external sources?   

    - APIs (Application Programming Interfaces) are sets of rules and protocols that allow different software applications to communicate and interact with each other. They define how different software components should interact, enabling data exchange and functionality integration between application


#### What is the Requests library in Python, and how can it be used to interact with APIs by sending HTTP requests? Can you provide an example of a basic GET request using the Requests library?

    - It provides a simple and intuitive interface to interact with APIs by sending HTTP requests and handling the responses. It abstracts away the complexities of manual request handling, such as establishing connections, managing cookies, handling redirects 
    
    - We then check the status code of the response using response.status_code. If the status code is 200 (indicating a successful response), we can access the response data using response.json()