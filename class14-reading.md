# Database Normalization
A process used to organize a database into tables and columns.The idea behind is is using a table for only a specific topic. 

- Limiting data to a sepcific topic prevents duplicate data,
- This prevents issues that result from database modicfications.
- Equally important, it simplifies queries.
- Modification anomolies may happen and normalization fixes them.
- Three anomalys that can incur are Insert anomaly, update anomaly, and deletion anomaly.
- Three common forms of database normalization: 1st, 2nd, andj 3rd normal form.

**First Normal Form** - Information stored ina relational table witch each column containing atomic values. No repeating groups of columns.
**Second Normal Form** - Table is in first normal form and all the columns depend on the table's primary key.
**Third Normal Form** - Table is in second normal form and all of its columns are not transitively dependent on the primary key.

## Attribution 
https://www.essentialsql.com/get-ready-to-learn-sql-database-normalization-explained-in-simple-english/
