# Data Modeling

1. **What type of database is the best fit for the complex query intensive environment?**
   For a complex query-intensive environment, a relational database like PostgreSQL or MySQL is often the best fit due to its robust querying capabilities and support for complex transactions.

2. **What type of database is the best fit for hierarchical data storage?**
   Hierarchical data storage is well-suited for a document-based NoSQL database such as MongoDB or Firebase Firestore, as it allows for nested data structures and flexible schema designs.

3. **Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend.**
   Scaling a SQL database typically involves vertically scaling by upgrading hardware, which can become expensive and limited. NoSQL databases, on the other hand, offer horizontal scalability by adding more servers, making them more flexible and cost-effective for handling large volumes of data.

4. **Among data tables, what is a one-to-many relationship and how do we “relate” them?**
   In a one-to-many relationship, one record in a table can be related to many records in another table. This is typically implemented by adding a foreign key in the "many" side table that references the primary key of the "one" side table.

5. **Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.**
   Prior to designing your relational database, it might be useful to create a diagram of the database tables and their relationships.

6. **Explain the difference between a primary and foreign key.**
   A primary key uniquely identifies each record in a table, while a foreign key establishes a link between two tables by referencing the primary key of another table.

7. **How do we treat keywords and parameters differently in SQL syntax?**
   In SQL syntax, keywords are reserved words used to perform specific actions, while parameters are placeholders for values that are passed into SQL statements to filter or manipulate data.

8. **Define normalization within the context of schemas and data.**
   Normalization is the process of organizing data in a database efficiently by reducing redundancy and dependency. It involves breaking down large tables into smaller ones and establishing relationships between them to minimize data duplication.

9. **Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**
   In a one-to-one relationship, each record in one table is associated with only one record in another table. In a one-to-many relationship, each record in one table can be associated with multiple records in another table. In a many-to-many relationship, multiple records in one table can be associated with multiple records in another table through a junction table.
