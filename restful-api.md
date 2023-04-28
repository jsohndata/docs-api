# A RESTful API
`Re`presentational `S`tate `T`ransfer API, is an architectural style for building web services. It is a set of guidelines for designing web services that are scalable, easy to maintain, and can be consumed by a wide range of clients from web apps and mobile apps.

RESTful APIs rely on the `HTTP protocol` to communicate between clients and servers, using HTTP methods such as `GET`, `POST`, `PUT`, `DELETE`, etc. 

<br>

## GET
* `/api/users`: Get all users
* `/api/users/{id}`: Get a specific user

## POST
* `/api/users`: Create a new user

## PUT
* `/api/users/{id}`: Update an existing user

## DELETE
* `/api/users/{id}`: Delete a user

<br>

## Explanation
The endpoints follow a consistent pattern to perform `CRUD` (Create, Read, Update, Delete) operations. 

<br>

## Summary
RESTful APIs provide a simple and standard way for web services to interact with each other, making it easier to create apps that can be integrated with different systems.