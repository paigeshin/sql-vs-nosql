# sql-vs-nosql
### Objective

- Different Kinds of Database (SQL vs NoSQL)
- Using SQL in a Node.js App

### SQL vs NoSQL

- Goal: Store Data and Make it Easily Accessible
- Use a Database!

⇒ SQL Databases 

⇒ NoSQL Databases

### SQL

- Using Tables
- fields & columns


### Core SQL Database Characteristics

- Data Schema  ⇒ All Data (in a Table) has to fit!
- Data Relations ⇒ Tables are connected
    - One-to-One
    - One-to-Many
    - Many-to-Many



### SQL Queries

- `SELECT * FROM users WHERE age > 28`


### NoSQL

- Collections (equivalent to Table, but we call it Collection)
- Document
- Schemaless
- Duplicate Data
- Very fast and efficient



### NoSQL Characteristics

- No Data Schema → No Structure required!
    - { name, id, age }
    - { id, age }
- NO Data Relations  → No / Few Connections
    - ❗️You can relate documents but you don't have to (and you shouldn't do it too much or your queries become slow)


# Scaling - Horizontal vs Vertical Scaling


### Horizontal Scaling

- Add More Servers (and merge Data into one Database)

### Vertical Scaling

- Improve Server Capacity / Hardware


### SQL - Difficult  for horizontal scaling

- Data uses Schemas
- Relations!
- Data is distributed across multiple tables
- Horizontal scaling is difficult / impossible; Vertical scaling is possible
- Limitations for lots of (thousands) read & write queries per second

### NoSQL - Easy for horizontal scaling

- Schema-less
- No (or very few) Relations
- Data is typically merged / nested in a few collections
- Both horizontal and vertical scaling is possible
- Great performance for mass read & write requests
