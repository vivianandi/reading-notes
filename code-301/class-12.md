# CRUD

## [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

**In your own words, describe what each group of status code represents:**
**100’s =** Informational status codes indicating that the server has received the request headers and will proceed with the client's request
**200’s =** Success codes indicating that the client's request was accepted and processed successfully
**300’s =** Redirection codes indicating that further action needs to be taken by the client to fulfill the request
**400’s =** Client error codes indicating that there was an issue with the client's request, such as invalid input or authentication errors
**500’s =** Server error codes indicating that there was an issue on the server side while processing the request

**What is a status code 202?**
- Indicates that the request was accepted for processing, but the processing has not been completed yet -> typically used for asynchronous operations

**What is a status code 308?**
- Indicates that the requested resource has permanently moved to a new URL and the client should directly access it via the new URL in the future

**What code would you use if an update didn’t return data to a client?**
204 No Content

**What code would you use if a resource used to exist but no longer does?**
410 Gone

**What is the ‘Forbidden’ status code?**
- Indicates that the client has been authenticated, but it does not have permission to access the requested resource

## [Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

**Why do we need to pull our MongoDB database string out of our server and put it into our .env?**
- Storing the MongoDB database string in a .env file enhances security by preventing sensitive information from being exposed in the codebase. It also allows for easier configuration management across different environments

**What is middleware?**
- Middleware functions are functions that have access to the request and response objects in an Express application's request-response cycle. They can execute code, modify request and response objects, end the request-response cycle, or call the next middleware function in the stack

**What does `app.use(express.json())` do?**
- It enables parsing of JSON-encoded request bodies -> this middleware function parses incoming request bodies with JSON payloads and makes the parsed data available on the `req.body` property

**What does the `/:id` mean in a route?**
- It represents a route parameter in `Express`, where `id` is a placeholder for a specific value that will be specified in the URL when making a request -> this allows for dynamic routing based on the value of `id`

**What is the difference between `PUT` and `PATCH`?**
- `PUT` is used to update an entire resource, replacing it with the request payload, while `PATCH` is used to apply partial modifications to a resource, typically specified in the request payload

**How do you make a default value in a schema?**
- You can specify default values for schema fields using the default property in Mongoose schema definitions

**What does a `500` error status code mean?**
- A `500` error status code indicates an internal server error -> it signifies that something went wrong on the server side while processing the request, and the server was unable to fulfill the request due to an unexpected condition

**What is the difference between a status `200` and a status `201`?**
- A status `200` indicates that the request was successful, whereas a status `201` specifically indicates that a new resource has been successfully created as a result of the request