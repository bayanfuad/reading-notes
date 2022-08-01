# Readings: APIs

## What does REST stand for?

Representational state transfer.

## REST APIs are designed around __.2000

## What is an identifier of a resource? Give an example.

it is URI, uniform resource identifier. as example : https://adventure-works.com/orders/1

## What are the most common HTTP verbs?

The most common operations are GET, POST, PUT, PATCH, and DELETE.

## What should the URIs be based on?

I think based on the data itself in API and the type of service also that provided by the API.
 
## Give an example of a good URI. 

like : /customers/1/orders/99/products , if i need the customers and will make the URI makes sense to the data requested by the user. here they used customer then the id of the desired customer and the orders and so on.

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing? 

when you make the client makes many requests to get a small amuont of data for each request (based on organizing the data in your API), this will make a load on your server and you have to aviod that. for sure it is bad thing.

## What status code does a successful GET request return?
status code 200 (ok)
## What status code does an unsuccessful GET request return?
status code 404 (Not Found)
## What status code does a successful POST request return?
status code 201 (Created)
## What status code does a successful DELETE request return?
status code 204 (deleted) RegExr

## Things I want to know more about
RestFul APIs and RegEx
