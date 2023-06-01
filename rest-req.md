A REST (Representational State Transfer) request is composed of several key elements:

**1. Endpoint (URL):**

The endpoint or URL is the web address where the request is sent. It usually points to a specific resource or a collection of resources on the server. For instance, `https://api.example.com/users` might be the endpoint to access users on a website.

**2. HTTP Method:**

This specifies the type of action to be performed on the resource. The common methods include:

- GET: Retrieve a resource or list of resources.
- POST: Create a new resource.
- PUT: Update an existing resource.
- DELETE: Delete a resource.
- PATCH: Partially update a resource.

**3. Headers:**

HTTP headers allow the client and the server to pass additional information with the request or the response. There are many different headers, but some commonly used ones are:

- `Content-Type`: This defines the media type of the request body sent to the server. Common values are `application/json`, `text/html`, and `multipart/form-data`.
- `Authorization`: This carries credentials for authenticating a user agent with a server.
- `Accept`: This defines the content types that the client is able to understand.
- `User-Agent`: This contains information about the client (e.g., browser or device type) making the request.

**4. Body (Payload):**

The body or payload is where data is included that you want to send to the server. This is usually included in POST and PUT requests where you are creating or updating a resource, respectively. The format of the body typically follows the `Content-Type` header, such as `application/json`.

**5. Query Parameters:**

Query parameters are optional and are used to modify the request with specific data, filtering, or other contextual information. They're appended to the end of the URL after a `?` character and are separated by `&` if more than one exists. For instance, in `https://api.example.com/users?sortBy=name&order=asc`, `sortBy` and `order` are query parameters.

**6. Path Parameters:**

Path parameters are variables within the URL itself and are often used to point to a specific resource. For example, in `https://api.example.com/users/123`, `123` is a path parameter representing a specific user's ID.

By composing these components correctly, you're able to make a wide variety of requests to interact with web services using RESTful APIs.
