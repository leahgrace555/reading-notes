# Database Normalization

- Process to organize a database into tables and columns

## Reasons to normalize
- Minimize duplicate data
- Minimiza or avoid data modification issues
- simplify queries

# Definitions: 

- **First Normal Form**: The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
- **Second Normal Form**: The table is in first normal form and all the columns depend on the table’s primary key.
- **Third Normal Form**: the table is in second normal form and all of its columns are not transitively dependent on the primary key
