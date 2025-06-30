COMPANY: CODTECH IT SOLUTIONS

NAME: GNANA PREETHIKA A B

DOMAIN: SQL

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH KUMAR



*Task 3: Database Migration*
This task demonstrates a simple yet effective example of database migration between two database systems – MySQL and PostgreSQL – with a focus on preserving data integrity and schema mapping. The goal is to simulate the transfer of data from a source table (representing a MySQL environment) to a target table (representing a PostgreSQL environment).

To begin with, we created two tables: books_mysql as the source table and library_pg as the target table. The books_mysql table simulates a typical table in a MySQL database and contains columns such as book_id, title, author, and price. These columns represent basic book information including the unique ID, book title, author's name, and the price of the book.

We then inserted sample data into books_mysql, adding three books: The Alchemist by Paulo Coelho, Atomic Habits by James Clear, and The Psychology of Money by Morgan Housel. These entries were chosen to mimic real-world records and provide a good testing ground for migration.

Next, the library_pg table was created to simulate the destination PostgreSQL table. This table contains similar columns but with slightly different names: book_id, book_title, book_author, and cost. These renamed columns reflect the common practice during database migrations where schema transformations or adjustments are often required to match target database naming conventions or standards.

The core of this task is the *data migration step*, where data from the MySQL-like books_mysql table is inserted into the PostgreSQL-like library_pg table. This is achieved using an INSERT INTO ... SELECT SQL query, which selects the required fields from the source table and maps them directly to the corresponding fields in the target table. This step highlights how data migration can be efficiently handled using SQL without external tools when dealing with compatible schemas.

Finally, a simple SELECT * FROM library_pg; query is executed to confirm that the data has been successfully migrated to the PostgreSQL table. The result reflects that all three books were transferred accurately, maintaining both data correctness and consistency between systems.

This exercise is a simplified version of real-world database migration scenarios, where moving data between different platforms (like MySQL to PostgreSQL) is a common need during system upgrades, consolidations, or cloud transitions. The example reinforces core database concepts such as data transformation, schema mapping, and migration scripting. It also shows how standard SQL can be used to handle cross-database tasks effectively without the need for complex tools or utilities.


OUTPUT:
![Image](https://github.com/user-attachments/assets/d70c42d9-26b4-455e-bd29-0fbfcda07cab) 
