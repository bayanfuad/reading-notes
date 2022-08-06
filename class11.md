# nosql vs sql

## Comparison between SQL and noSQL

 SQL                        |     NoSQL
 ---------------------------|------------------------------------------ 
  Relational Databases      |  non-relational or distributed database. 
 table based databases      | document based
 have predefined schema     | dynamic schema
 vertically scalable        | horizontally scalable
 structured query language  | Unstructured Query Language
 
## What kind of data is a good fit for an SQL database?

SQL databases are good fit for the complex query intensive environment whereas NoSQL databases are not good fit for complex queries.

If your data is highly structured and associations among the program entities are clearly defined.

## Give a real world example.

for instance, if you are developing a point of sale system where you need to store customer orders and product records

## What kind of data is a good fit a NoSQL database?

large data with simple schema

## Give a real world example.

Social games are data-intensive applications that can explode from zero to millions of players literally overnight. That kind of rapid growth, both in terms of data volume and number of users, necessitates the right class of database to store all that information and scale to a growing user base. NoSQL provides scalability, consistently high performance, always-on 24×365 operations and a flexible data model. Some of the most popular social and mobile games come from the likes of Zynga, Electronic Arts, Tencent and Shuffle Master, which are all powered by NoSQL.

## Which type of database is best for hierarchical data storage?

noSQL

## Which type of database is best for scalability?

NoSQL, earning it's name by being “not only SQL” makes it easier to store all different types of data together. It's used for its flexibility and therefore speed and scalability in managing large volumes of data.

Source
sql vs nosql
## What does SQL stand for?

Structured Query Language

## SELECT id, name, price FROM products

bold are SQL syntax / keywords
normal are Data/Parameters
What is a relational database?
we have a database which works with certain assumptions or in a certain way and it supports the sq language

## What type of structure does a relational database work with?

Tables - like a storage container

## What is a ‘schema’?

when we query data with sql, we will have a very strict requirements for the data we store in our database table, it is also called fields

## What is a NoSQL database?

it is also called MongoDB which stands for Humongous because it can store lots and lots of data in a very effiecient way.

## How does it work?

we have data bases and we have collections instead of tables and inside it we have documents (rows and tables) they look like JSON and they dont have to use the same schema, we can have multiple documents in one collection which have different fields.

# What is inside of a Mongo database?

## Which is more flexible - SQL or MongoDB? and why.
MongoDB

You can add new data, and you want to fetch new data at some point, you can store them in the same collection.
There is also no/few relations.
## What is the disadvantage of a NoSQL database?

You could have duplicated data, it needs to be updated

## Things I want to know more about

Mongo and SQL
