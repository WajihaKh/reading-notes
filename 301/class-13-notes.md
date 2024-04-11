# More CRUD

**Which HTTP method would you use to update a record through an API?**

- You would use the HTTP method PUT to update a record through an API. The PUT method is used to replace or update an existing resource entirely with a new one at the specified URL.

**Which REST methods require an ID parameter?**

The REST methods that require an ID parameter typically include:

- GET (Retrieve): When retrieving a specific resource, such as /appointments/:id to get details of a specific appointment.
- PUT (Update): When updating a specific resource, such as /appointments/:id to update details of a specific appointment.
- DELETE (Delete): When deleting a specific resource, such as /appointments/:id to delete a specific appointment.

**What’s the relationship between REST and CRUD?**

- Resource Identification: RESTful APIs use unique URLs to identify resources (e.g., /appointments/:id), where the :id parameter specifies a specific resource.

- CRUD Operations as HTTP Methods:

  - Create: POST method creates new resources (e.g., /appointments).
  - Read: GET method retrieves existing resources (e.g., /appointments/:id).
  - Update: PUT or PATCH methods modify existing resources (e.g., /appointments/:id).
    -Delete: DELETE method removes existing resources (e.g., /appointments/:id).
Statelessness and Uniform Interface: REST emphasizes statelessness and a consistent interface using standard HTTP methods for CRUD operations.

**If you had to describe the process of creating a RESTful API in 5 steps, what would they be?**

Define resource endpoints and map HTTP methods (GET, POST, PUT, PATCH, DELETE) to CRUD operations.
Implement endpoint logic to handle requests, design data formats for requests/responses, and thoroughly test and document the API.
