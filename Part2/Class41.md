# Class 41

## React 4

## [Link](./Class41.md)

#### Explain the concept of dynamic routes in Next.js and how they differ from static routes.

    - In Next.js, a popular React framework for building web applications, dynamic routes and static routes are two different approaches to handling routing and rendering of content. They serve different purposes and have distinct characteristics.

    - Static Routes

    - Dynamic Routes

    - static routes are pre-rendered at build time and are suitable for content that doesn't change often, while dynamic routes are generated on the server side at runtime and are used for content that depends on user input or data that's only available during the request.

    

#### Describe the process of deploying a Next.js application. What are the key steps involved, and what are some deployment platforms you can use?

    - a Next.js application involves a series of steps to make your application accessible to users on the web.

      - Optimize and Build

      - Choose a Hosting Provider

      - Create a Deployment Configuration

      - Deploy Your Application

      - Configure Domain and SSL

      - Testing and Monitoring


#### How does Next.js handle static file serving? Discuss the default folder structure for storing static assets and explain how to reference them in a Next.js application

    - By default, Next.js looks for static files in a folder named public at the root level of your project. This public folder is where you should place your static assets

     - Next.js provides a way to serve static files alongside your dynamic pages and components. Static files can include images, stylesheets, fonts, and other assets that don't require server-side processing

     -  Next.js uses the public folder to serve static assets and automatically maps URLs to the root URL of your application. This approach ensures optimized caching and efficient serving of static files.
     