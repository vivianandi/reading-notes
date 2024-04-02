# APIs

## [API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
**What does REST stand for?**
- Representational State Transfer

**REST APIs are designed around a ____.**
- Resources

**What is an identifier of a resource? Give an example.**
- An identifier of a resource is a URI (Uniform Resource Identifier). Example: `https://adventure-works.com/orders/1`

**What are the most common HTTP verbs?**
- GET, POST, PUT, PATCH, DELETE

**What should the URIs be based on?**
- URIs should be based on nouns (the resource) and not verbs (the operations on the resource)

**Give an example of a good URI.**
- `https://adventure-works.com/orders`

**What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**
- A 'chatty' web API exposes a large number of small resources, leading to increased requests and server load -> this is generally considered a bad thing as it can result in decreased performance

**What status code does a successful GET request return?**
- HTTP status code 200 (OK)

**What status code does an unsuccessful GET request return?**
- HTTP status code 404 (Not Found)

**What status code does a successful POST request return?**
- HTTP status code 201 (Created)

**What status code does a successful DELETE request return?**
- HTTP status code 204 (No Content)

## Resources
[RegExr](https://regexr.com/)
- Pay particular attention to the cheatsheet
[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
[Regex 101](https://regex101.com/)