# WeLoveMovies Backend & API

## Overview

This repository contains the backend and API for the WeLoveMovies website. The purpose of this project is to facilitate the storage and delivery of movie-related data, including information about movies, theaters, and user reviews. The backend is designed to handle various API endpoints and interact with a PostgreSQL database using Knex for data manipulation.

## Project Requirements

The following are the requirements for this project:

1. **Setting up common middleware packages**: Common middleware packages such as `express`, `helmet`, `cors`, and `morgan` are configured to ensure security, logging, and proper handling of HTTP requests.

2. **Setting up routes to receive requests**: Routes are defined to handle incoming HTTP requests and route them to the appropriate controller functions.

3. **Use routes and query parameters to access relevant information**: Routes and query parameters are used to access and retrieve relevant data from the database based on user requests.

4. **Setting up error handlers**: Error handling middleware is implemented to gracefully handle errors and provide informative responses to clients.

5. **An API that follows RESTful design principles**: The API follows RESTful design principles, ensuring that endpoints and HTTP methods are structured in a RESTful manner.

6. **Setting up and customizing knexfile**: The `knexfile.js` is configured and customized to specify the database connection details and other relevant settings for Knex.

7. **Utilizing Knex to connect to my PostgreSQL database**: Knex is used to establish a connection to the PostgreSQL database, enabling data querying and manipulation.

8. **Database migrations with Knex**: Database migrations are used to create and modify database tables and schemas, allowing for version control of the database schema.

9. **Deployment of my backend server (Render)**: The backend server is deployed on the Render platform, making the API accessible over the internet.

## Links
- [App Demo](TBD)
- [App Documentation](https://github.com/GPVcode/We-Love-Movies-Project)

## Screenshot
### Home Page:
![home](/assets/WLMHome.png)

## Technology
Built with:
- Node.js
  - Express server framework
  - CORS package
- PostgreSQL database
  - Knex.js for query building

## Deployment

This project is deployed on the Render platform. To deploy your own instance, follow these steps:

1. Create an account on Render if you don't already have one.

2. Set up a new web service and connect it to your GitHub repository.

3. Configure the environment variables required for your application, including database connection details.

4. Deploy your application to Render.

## Conclusion

The WeLoveMovies Backend & API is a comprehensive solution for managing movie-related data and providing a RESTful API for client applications. By following the instructions in this README, you can set up, customize, and deploy your own instance of the backend server. Please refer to the API documentation for usage details and enjoy using this API in your projects!
