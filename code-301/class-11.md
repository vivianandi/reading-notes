# MongoDB and Mongoose

## [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)
**Fill in the chart below with five differences between SQL and NoSQL databases:**
**SQL	NoSQL**
Here are five differences between SQL and NoSQL databases:

| SQL                             | NoSQL                                    |
|---------------------------------|------------------------------------------|
| Data is stored in tables with a predefined schema. | Data is stored in various formats such as key-value pairs, documents, graphs, or wide-column stores without a predefined schema. |
| Queries are performed using SQL (Structured Query Language). | Queries are focused on collections of documents or data structures specific to each NoSQL database, sometimes referred to as UnQL (Unstructured Query Language). |
| Suitable for complex queries and transactions. | Not a good fit for complex queries; more suitable for high volume and velocity data. |
| Vertically scalable, meaning you can increase the capacity of a single server. | Horizontally scalable, meaning you can distribute the database load across multiple servers. |
| Examples include MySQL, PostgreSQL, Oracle. | Examples include MongoDB, Cassandra, Redis. |


**What kind of data is a good fit for an SQL database?**
- Structured data with a predefined schema
- Data requiring complex queries and transactions
- Suitable for applications with ACID properties

**Give a real world example.**
- Online transaction processing systems (e.g., banking systems) where data integrity and consistency are crucial

**What kind of data is a good fit a NoSQL database?**
- Unstructured or semi-structured data
- High volume and velocity data, such as big data and real-time data
- Suitable for applications requiring horizontal scalability

**Give a real world example.**
- Social media platforms

**Which type of database is best for hierarchical data storage?**
- NoSQL databases are typically a better fit due to their support for key-value pairs and document-based structures, which align well with hierarchical data storage

**Which type of database is best for scalability?**
- NoSQL databases are generally better suited for scalability

## [sql vs nosql (Video)](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
**What does SQL stand for?**
- SQL stands for Structured Query Language

**What is a relational database?**
- A relational database is a type of database that stores and organizes data into tables, where data relationships are established through keys

**What type of structure does a relational database work with?**
- Relational databases work with a tabular structure, where data is organized into rows and columns within tables

**What is a ‘schema’?**
- A schema is a formal description of the structure of a database, including the tables, fields, and relationships between them

**What is a NoSQL database?**
- A NoSQL (Not Only SQL) database is a type of database that provides a mechanism for storage and retrieval of data in formats other than the tabular relations used in relational databases

**How does it work?**
- NoSQL databases work with flexible schemas and can store data in various formats such as key-value pairs, documents, graphs, or wide-column stores

**What is inside of a MongoDB database?**
- MongoDB stores data in JSON-like documents, which are flexible and can vary in structure from one document to another within the same collection

**Which is more flexible - SQL or MongoDB? and why.**
- MongoDB is generally considered more flexible due to its schema-less nature -> unlike SQL databases, which have rigid schemas, MongoDB allows for dynamic schema evolution, making it easier to adapt to changing data requirements

**What is the disadvantage of a NoSQL database?**
- One disadvantage of NoSQL databases is the lack of standardization in query languages and tools compared to SQL databases -> additionally, NoSQL databases may not provide the same level of support for complex queries and transactions as SQL databases do

## Resources
[mongoose api](https://mongoosejs.com/docs/api/model.html#Model)
[React Router](https://reactrouter.com/en/6.20.1/router-components/browser-router)