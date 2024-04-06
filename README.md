# ejs_partials_project

Brief description of your project.

## Table of Contents

- [Configuration](#configuration)
- [Static File Serving](#static-file-serving)
- [Routing](#routing)
- [Server Startup](#server-startup)

## Configuration

This code snippet configures an Express.js application to serve static files, render EJS templates, and listen on a specified port.

## Static File Serving

The `express.static` middleware serves static files, in this case, from the `public` directory. This allows the application to serve HTML, CSS, JavaScript, and other static assets.

## Routing

The application defines GET routes for three pages:

1. `/`: Renders the `index.ejs` template as the homepage.
2. `/about`: Renders the `about.ejs` template for the about page.
3. `/contact`: Renders the `contact.ejs` template for the contact page.

## Server Startup

The `app.listen` method starts the Express.js application and listens on the specified port (3000). Once the server starts, it logs a message to the console indicating that it is running.

1. Clone the repository:

   ```bash
   https://github.com/adityadhiman-in/ejs_partials_project.git

   ```

1. Navigate to the project directory:

`cd yourproject`

2 Install dependencies:

`npm install`

Start the server:

`node index.js`
