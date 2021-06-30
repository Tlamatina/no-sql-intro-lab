# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?

* When people use the term “NoSQL database”, they typically use it to refer to any non-relational database. Some say the term “NoSQL” stands for “non SQL” while others say it stands for “not only SQL.” Either way, most agree that NoSQL databases are databases that store data in a format other than relational tables.

2. What are some of the common arguments for using a non-relational versus a relational db?

* NoSQL databases can store relationship data—they just store it differently than relational databases do. In fact, when compared with SQL databases, many find modeling relationship data in NoSQL databases to be easier than in SQL databases, because related data doesn’t have to be split between tables.


3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 

* A non-relational database is a database that does not use the tabular schema of rows and columns found in most traditional database systems. Instead, non-relational databases use a storage model that is optimized for the specific requirements of the type of data being stored. For example, data may be stored as simple key/value pairs, as JSON documents, or as a graph consisting of edges and vertices. 

https://docs.microsoft.com/en-us/azure/architecture/data-guide/big-data/non-relational-data


4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?

SQL databases are used to store structured data while NoSQL databases like MongoDB are used to save unstructured data.
MongoDB is used to save unstructured data in JSON format.
MongoDB does not support advanced analytics and joins like SQL databases support.

https://www.knowi.com/blog/mongodb-vs-sql/


5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 

* Example user table in Postgres:

id	username	password	email
1	tlamatina	12345678	tassi.lamatina@gmail.com

* Example user document in Mongo:

{   _id: <ObjectID>,
    username: "tlamatina",
    password: "12345678",
    email: "tassi.lamatina@gmail.com"
}


6. What is an example situation where a Mongo database makes sense versus a non-relational db?

* If you and your job likes Mongo DB. If you want to be able to add data in an unstructured way to large DB intead of initial stubbing.

