1. In your own words, describe what each group of status code represents:

100’s = status code that tells the client the initial request has been received. 
200’s = success codes that tell the client if the request was accepted.
300’s = redirection codes tell the client the location of the request is not available.
400’s = error codes tell the client the request is invalid.
500’s = server error code when there is a problem with the server.

2. What is a status code 202?

Accepted


3. What is a status code 308?

Permanent Redirect


4. What code would you use if an update didn’t return data to a client?

204 No Content 


5. What code would you use if a resource used to exist but no longer does?

410 Gone


6. What is the ‘Forbidden’ status code?

When the client does not have permission to access the resource. 

 

(https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/ Links to an external site.).

 

Videos
Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

Because we will use something other than our local host.


2. What is middleware?

Code that runs when the server gets a request but before it gets passed to the routes.


3. What does app.use(express.json()) do?

It lets our server accept JSON as a body instead of a post element.


4. What does the /:id mean in a route?

Makes id a parameter so it can be used.


5. What is the difference between PUT and PATCH?

PATCH only updates what the user passes us.

PUT updates all information all at once.


6. How do you make a default value in a schema?

default: Something.now


7. What does a 500 error status code mean?

When there is an error with the server.


8. What is the difference between a status 200 and a status 201?

200 is everything is ok.

201 means created. 

 

(
https://www.youtube.com/watch?v=fgTGADljAeg&t=1sLinks to an external site.
).

 