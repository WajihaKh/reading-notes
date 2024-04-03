# API's

__What does REST stand for?__

Representational State Transfer

**REST APIs are designed around a ____.**

Resource

__What is an identifier of a resource? Give an example.__

An identifier of a resource is a URI
Ex. http://api.example.com/customers/123

__What are the most common HTTP verbs?__

- GET
- POST
- PUT
- PATCH
- DELETE

__What should the URIs be based on?__

Resources

__Give an example of a good URI.__

http://api.example.com/orders

__What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?__

It requires multiple requests to accomplish a single task which can lead to increased latency and network overhead. It's considered a bad thing as it reduces the efficiency and performance of the API.

__What status code does a successful GET request return?__

Returns HTTP status code 200

__What status code does an unsuccessful GET request return?__

Returns HTTP status code 404

__What status code does a successful POST request return?__

Returns HTTP status code 201

__What status code does a successful DELETE request return?__

Returns HTTP status code 204
