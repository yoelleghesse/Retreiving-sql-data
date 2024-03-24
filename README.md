This script demonstrates how to execute SQL queries on an SQLite database using Python's sqlite3 module. It performs the following queries:

- Get all rows and all columns from the ips table, ordered by ASN.
- Get only the address and asn columns from the ips table, ordered by ASN.
- Get all rows from the ips table where ASN is less than 300.
- Get all rows from the ips table where ASN is 144.
- Get all rows from the ips table where ASN is less than 300 and the domain ends with 'sa'.
- Print the results of the last query row by row.

Ensure that you have the SQLite database database.db with the appropriate schema and data.

Execute the Python script to perform the SQL queries:

``python sqlite_queries.py``

Ensure that the database.db file exists in the same directory as the script and adjust the SQL queries and table names as needed to match your database schema.
