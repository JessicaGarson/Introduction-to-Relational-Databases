# Introduction to Relational Databases

## Slides
Slides are found [here]()

## Hello
Hi, I'm Jessica Garson. I got my start working on political campaigns all over the country and one day some data came into my life. I wrote some code to fix it and that was transformative moment for me. After that I went to work in tech and worked at start up doing tech support where my favorite part of my job was writing SQL queries, because I got to be a detective and find out why something happened the way it did.

## Let's Meet a New Friend
Let's meet someone new and exchange the following information
- Name
- One sentence bio
- Why do you want to learn SQL
- Favorite candy bar

## Norms for Today
Norms allow us to us to define what is and isn't acceptable in a training space. Some sample norms include.
- Don't be afraid to not the know the answer
- Step up, step back
- No shame in googling the answer
- We will get errors today
- If you need help, ask for it
- If the material is coming naturally for you, help a neighbor out
- Others?

## Objectives for Today
By the end of today's lesson we will be able to answer the following questions:
- What is SQL and why do we use it?
- What is a relational database?

## What is SQL?
SQL stands for Structured Query Language. It is a language that allows us to work with complex datasets. We can use SQL to get the information we need from a dataset.

## The S is for Structured
- Data in a SQL database is stored in pre-defined tables
- Tables are populated by fields with prescribed data types

Examples of data types:
- INTEGER, i.e. 1234
- VARCHAR and TEXT, i.e. “Jessica Garson”
- FLOAT and DOUBLE and DECIMAL, i.e. 3.14159
- DATE and TIMESTAMP, i.e. 2013-04-15

## The Q is for Query
- A query is a question or command issued to the database

Examples:

- Find all the members who are subscribed to my email list
- Find all donations that are greater than $50.00
- Insert new records into the database from “new_members_febuary_2018.csv”

## The L is for Language
As a language, SQL has its own syntax

- A syntax is basically a language’s grammar, and the words that can be used in
that language, the order that is required, and the way each command relates to
the others

## Flavors of SQL
- MySQL
- PostgreSQL
- SQLite
- Maria DB
- Oracle
- MS SQL Server
- Others too!

## But I got Excel?
While Excel is great, it's not always the best for working with all datasets.
- Can crash with too many rows or too many complex functions
- It can truncate data
- Difficult to handle messy/complex datasets
- Difficult to connect multiple datasets

## Why SQL?
- SQL can handle large and complex datasets
- SQL can quickly retrieve information about many different, but related datasets
- SQL can be “scripted” and automated

## CRUD
Create - add a new record to a table

Read - get a subset of data from one or more tables (can include operations
performed on that data)

Update - change the fields of one or more existing records

Destroy - remove a record from a table

## What is a Relational Database
The term relational databases refers to how data can connect with each other.


## Major Key Alert
The key to SQL is keys!
- Primary keys are the unique identifier of each record in a database

- Foreign keys are special fields within a table that contain the primary key, or any field, of a record from another table

## Types of Relationships
One-to-one
- Think a table with SSNs and a table with People

One-to-many
- Think a table with Members and a Table with Donations

Many-to-many
- Think a table with authors and books
