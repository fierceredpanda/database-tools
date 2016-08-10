# database-tools
Tools for populating relational databases.

##### DataLoader

`com.intersysconsulting.database.tools.examples.data.DataLoader` can be used to load data into a MySQL database.  This tool connects to the database, reads the schema for the table and will generate random data to populate the table.  The arguments are as follows:

1. server - The hostname and the port of the database to populate. Example: localhost:3306
2. database - The name of the database / schema to insert data into
3. user - The user to use when connecting to the database.
4. password - The password to use when connecting to the database.
5. table - The table to insert data into.
6. numBatches - The number of batches to execute (2.5 second delay between batches)
7. itemsPerBatch - The number of records to insert for each batch.

