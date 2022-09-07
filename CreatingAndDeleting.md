## Notes

1. In your own words, describe what each group of status code represents:

   - 100's =The request is received by the server and the client is okay to continue.
   - 200's =The request is succesfully completed.
   - 300's =Redirection your request to another url
   - 400's =Something’s wrong with the request
   - 500's =The server can't access to this web page

1. What is a status code 202? That the client's request has been accepted for processing, but the processing has not been completed
1. What is a status code 308? The resource requested has been definitively moved to the URL given by the Location headers
1. What code would you use if an update didn't return data to a client? 204 No Content
1. What code would you use if a resource used to exist but no longer does?409
1. What is the 'Forbidden' status code?403

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env? maybe to be hidden
1. What is middleware? Middleware is software that provides common services and capabilities to applications outside of what’s offered by the operating system.
1. What does `app.use(express.json())` do?
   s a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app
1. What does the `/:id` mean in a route?a unique identifier assigned to every order that is protected by Route Package Protection.
1. What is the difference between `PUT` and `PATCH`?
   The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.
1. How do you make a default value in a schema? we can set the default schema option to a function
1. What does a `500` error status code mean?SERVER ERROR
1. What is the difference between a status `200` and a status `201`?The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created.
