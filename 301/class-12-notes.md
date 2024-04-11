# CRUD

**In your own words, describe what each group of status code represents:**

100’s = These codes give early information to the client that the server has received the request and will continue to process it.
200’s = These codes indicate that the client's request was successful and accepted by the server.
300’s = These codes tell the client that the request resource has moved or requires additional steps to complete the request.
400’s = These codes indicate that there was an issue with the client's request, such as invalid syntax or unauthorized access.
500’s = These codes indicate that there was a problem on the server's end while processing a valid request from the client

**What is a status code 202?**

The server has accepted the request for processing but the processing is not yet complete.

**What is a status code 308?**

The request resouce has permanently moved to a new location.

**What code would you use if an update didn’t return data to a client?**

We would use status code 204 to indicate that the sever processed the update successfully but it not returning any content.

**What code would you use if a resource used to exist but no longer does?**

We would use code 410 to inform the client that the request resource is no longer available.

**What is the ‘Forbidden’ status code?**

403, server understood the request but refuses to authorize it due to insufficient permissions.

**Why do we need to pull our MongoDB database string out of our server and put it into our .env?**

We need to pull our MongoDB database string out of our server and put it into our .env for security purposes because storing sensitive information exposes it to potential leaks or unauthorized access. The env file allows us to keep information private.

**What is middleware?**

Middleware is a software that acts as a bridge between different systems, applications or components allowing them to communciate and interact with each other.

**What does app.use(express.json()) do?**

Helps the server to understand and work with incoming JSON data from client requests. It automatically parses the JSON data and makes it accessible in 'req.body', simplifying how the server handles JSON payload without needing manual parsing.

**What does the /:id mean in a route?**

Captures a variable value from the URL. Placeholder that represents a specific identifier and allows you to access this value in your route handler.

**What is the difference between PUT and PATCH?**

- PUT: When you want to replace a resource entirely with the provided representation.

- PATCH: When you want to apply partial updates to a resource by specifying only the fields that need to be changed. More suitable for updating specific parts of a resource without affecting the entire resource representation.

**How do you make a default value in a schema?**

To make a refault value in a schema, you can use the 'default' propert when defining a field. This default value will be assigned if no value is provided for that field when creating a new document.

**What does a 500 error status code mean?**

Unexpected condition or problem on the server side that prevented it from fulfilling a request made by the client.

**What is the difference between a status 200 and a status 201?**

- 200: for successful request that don't involve creating new resources.

- 201: for indication successful creation of a new resrouce in response to a POST request.
