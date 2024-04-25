# HTTP status codes indicate the result of the request.

### Below are some of the commonly used HTTP status codes and their meanings:

### 1xx: Information
- 100 contiunue: indicate to client to contine with request 
- 101 switching protocols

### 2xx: Successful
- 200 OK: Successful transaction
- 201 Created: Request succeeded and a new resource was created as a result. Usually in response to a POST or PUT

### 3xx: Redirection
- 301 Moved Permanently: The URL of the resource permanently moved and the new URL has been provided in response

### 4xx: Client Error
- 400 Bad Request: Server did not understand client request
- 401 Unauthorized: Request requires authentication
- 403 Forbidden: client doesnt not have access rights to the resource
- 404 Not Found: server cannot find a requested resource

### 5xx: Server Error
- 500 Internal Server Error: Server has encountered an inssure it doesnt know how to handle
- 501 Not Implemented: Request is not supported by server and cannot be handeled/accepted
- 502 Bad Gateway: Server received an invaid request from another server/proxy while acting as a gateway/proxy
- 503 Service Unavailable: Server is not ready to hande the request. Most likely due to the server being down or being over loaded.
- 504 Gateway Timeout: server did not receive a response in time while acting as a gateway/proxy

### Resources:
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Status#information_responses
- https://www.geeksforgeeks.org/what-are-http-status-codes/
- https://httpstatus.io/http-status-codes
