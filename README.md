Objective
Understand middleware in Express.
Create and use custom middleware.
Explore and use third-party middleware.
Instructions
Project Initialization

Create a new directory named express-middleware.
Navigate into the directory.
Initialize a new Node.js project.
Install Express.
Create the Server

Create a file named index.js.
Set up a basic Express server that listens on port 3000.
Create a route that responds with "Hello, World!" at the root URL.
Create Custom Middleware

Add a custom middleware function that logs the details of each incoming request.
Ensure the middleware is used before defining the routes.
Test Custom Middleware

Start the server using Nodemon.
Make a request to the root URL and verify that the request details are logged in the console.
Use Third-Party Middleware

Install body-parser.
Modify the server to use body-parser to parse JSON bodies.
Create a POST route at /contact that responds with the parsed JSON data.
Test Third-Party Middleware

Start the server using Nodemon.
Use Thunder Client or Postman to send a POST request to /contact with a JSON body.
Verify that the parsed JSON data is included in the response.
Explore Middleware Stack

Create another custom middleware function that logs request headers.
Ensure the middleware functions are executed in the correct order.
