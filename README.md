# WeLoveMovies Backend & API
Built the backend and API of WeLoveMovies website to facilitate storage and delivery of the site's movies, theaters, and reviews data.

Assignment Requirements:

- Setting up common middleware packages
- Setting up routes to receive requests
- Use routes and query parameters to access relevant information
- Setting up error handlers
- An API that follows RESTful design principles
- Setting up and customizing knexfile
- Utilizing Knex to connect to my PostgreSQL database
- Database migrations with Knex
- Deployment of my backend server (Render)

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

## API Documentation
All requests return JSON response. All post requests require application/json body, and return JSON response.

Installation
Fork and clone this repository.
Run cp ./.env.sample ./.env.
Update the .env file with the connection URL's to your database instance.
Run npm install to install project dependencies.
Run npm run start:dev to start your server in development mode.