# CRUD
## In your own words, describe what each group of status code represents: 

100’s = indicates that everything is OK and that the client should continue with the request or ignore it if it is already finished
200’s = indicates that the request has succeeded. A 200 response is cacheable by default. The meaning of a success depends on the HTTP request method: GET : The resource has been fetched and is transmitted in the message body.
300’s = indicates that the request has more than one possible responses. The user-agent or the user should choose one of them. As there is no standardized way of choosing one of the responses, this response code is very rarely used.
400’s = indicates that the server cannot or will not process the request due to something that is perceived to be a client error (for example, malformed request syntax, invalid request message framing, or deceptive request routing).
500’s = indicates that the server encountered an unexpected condition that prevented it from fulfilling the request. This error is usually returned by the server when no other error code is suitable.

## What is a status code 202?

Accepted, this code tells the client that the request has been accepted for processing, but the processing has not been completed.

## What is a status code 308?

Permanent Redirect, this code tells the client that the resource they are requesting has been moved permanently to a new location.

## What code would you use if an update didn’t return data to a client?

204 No Content

## What code would you use if a resource used to exist but no longer does?

410 Gone

## What is the ‘Forbidden’ status code?

403 Forbidden, this code tells the client that the server is refusing to fulfill the request.

## Why do we need to pull our MongoDB database string out of our server and put it into our .env?

So that we can hide our database string from the public.

## What is middleware?**

Middleware is software that provides common services and capabilities to applications outside of what’s offered by the operating system. 
Data management, application services, messaging, authentication, and API management are all commonly handled by middleware.

## What does app.use(express.json()) do?**

recognize the incoming Request Object as a JSON Object.

## What does the /:id mean in a route?**

It's mean a key of object which you are shown in the database and declared by default.


## What is the difference beween PUT and PATCH?**

when you want to update a resource with PUT request, you have to send the full payload as the request whereas with PATCH ,
you only send the parameters which you want to update. Related: Suppose we have a resource that holds the first name and last name of a person.

## How do you make a default value in a schema?**

Make mongoose string schema type default value as blank and make the field optional. 
testschema = mongoose. Schema({ name:{ type:String, required:true, unique:true }, image:{ type:String, required:true }, category:{ type:String }, })/

## What does a 500 error status code mean?**

Internal Server Error server error response code

## What is the difference between a status 200 and a status 201?**

Successful. The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed.
A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).

## Things I want to know more about
CRUD
