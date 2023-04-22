## MongoDB and Mongoose
 
1. Five differences between SQL and NoSQL:
SQL-NoSQL
   1.Structured Query Language - used for Relational Databases - Non-relational or distributed database systems 
   2. Follows a fixed schema - Does not follow any fixed schema
   3.Good for handling structured data - Good for handling unstructured or semi-structured data
   4.Provides ACID (Atomicity, Consistency, Isolation, Durability) compliance - Does not always provide ACID compliance
   5.Examples: MySQL, Oracle, PostgreSQL - Examples: MongoDB, Cassandra, Couchbase

2. Structured data with well-defined relationships and fixed schema are good fit for SQL databases. Examples include financial transactions, customer data, and inventory management.

3. Unstructured or semi-structured data that does not fit into a rigid schema is a good fit for NoSQL databases. Examples include social media posts, sensor data, and multimedia content.

4. Hierarchical data storage is best suited for NoSQL databases, particularly document-oriented databases such as MongoDB.

5. Scalability is best achieved with NoSQL databases as they can easily distribute data across multiple servers and scale horizontally. SQL databases can also be scaled, but they require more effort and planning.


Videos:

1. SQL stands for Structured Query Language.

2. A relational database is a type of database that organizes data into one or more tables or relations. 

3. A relational database works with a tabular structure, where data is organized into tables or relations with fixed schema.

4. A schema is the logical structure or blueprint of a database that defines the relationships and constraints between tables, the data types and formats of columns, and the rules for manipulating data.

5. A NoSQL database is a non-relational database that uses a flexible, document-oriented or key-value data model to store and retrieve data. 

6. NoSQL databases work by storing and retrieving data in a flexible, schema-less way. Instead of tables, data is stored in documents, collections, or key-value pairs, which can be easily added, updated, or deleted without a predefined schema.

7. A MongoDB database contains collections of JSON-like documents that can have varying structures and field types. It stores data in a flexible, document-oriented format that allows for easy querying and indexing.

8. MongoDB is more flexible than SQL because it does not enforce a fixed schema, and documents can have varying structures and fields. This makes it easier to handle unstructured or semi-structured data and adapt to changing data requirements.

9. One disadvantage of NoSQL databases is that they may sacrifice some degree of data consistency or transactional guarantees in favor of scalability and performance. Additionally, NoSQL databases may have a steeper learning curve or require specialized skills compared to traditional SQL databases.


## Things I would like to know more about