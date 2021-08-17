# CRUD

### In your own words, describe what each group of status code represents

1. 100’s =Continue
2. 200’s =OK
2. 300’s =Multiple Choices
2. 400’s =Bad Request
2. 500’s =Internal Server Error



### What is a status code 202?
The HyperText Transfer Protocol (HTTP) 202 Accepted response status code indicates that the request has been accepted for processing, but the processing has not been completed; in fact, processing may not have started yet

### What is a status code 308?
The HyperText Transfer Protocol (HTTP) 308 Permanent Redirect redirect status response code indicates that the resource requested has been definitively moved to the URL given by the Location headers. ... Note: Some Web applications may use the 308 Permanent Redirect in a non-standard way and for other purposes.

### What code would you use if an update didn’t return data to a client?
`404` 

### What code would you use if a resource used to exist but no longer does?
`409 Conflict`

### What is the ‘Forbidden’ status code?
indicates that the server understood the request but refuses to authorize it

--------------------------------

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?
becouse it a sensative data 

### What is middleware?
basically a function that will the receive the Request and Response objects

### What does app.use(express.json()) do?
to recognize the incoming Request Object as a JSON Object

### what does the id mean in a route node.js

to build a dynamic route

### what is the difference between put and patch node js
PUT is a method of modifying resource where the client sends partial data that to be updated without modifying the entire data . With PATCH, however, the enclosed entity contains a set of instructions describing how a resource currently residing on the origin server should be modified to produce a new version.

### how do you make a default value in a schema mongoose
Make mongoose string schema type default value as blank and make the field optional.

### What does a 500 error status code mean?
(HTTP) 500 Internal Server Error server error response

### What is the difference between a status 200 and a status 201?

200:hat the request was received and understood
201:that a request was successful and as a result

