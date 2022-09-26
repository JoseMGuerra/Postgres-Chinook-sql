![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Working with PostgreSql DataBase.

Download the PostgreSql Chinook DataBase form GitHub to our WorkSpace:

![wget-chinook](readme-images/wget-chinnok.png)

## PostgreSql CLI Commands:

The [wget](https://shapeshed.com/unix-wget/#what-is-the-wget-command) command is a command line utility for downloading files from the Internet.

The [psql](https://www.postgresql.org/docs/current/app-psql.html) command to launch the PostgreSql database.
 - If you get the following error after typing psql in the terminal:

    "psql: error: could not connect to server: No such file or directory".

    Please use the following command in the terminal to set an environment variable needed for it to work:

    "set_pg"

    And then try the psql command again.

The  [\l](https://www.postgresqltutorial.com/postgresql-administration/postgresql-show-databases/)  command to list all databases in the current PostgreSQL database server.

The [CREATE DATABASE](https://www.w3schools.com/sql/sql_create_db.asp) statement is used to create a new SQL database. (In our case CREATE DATABASE chinook;)

The [\c](https://www.postgresqltutorial.com/postgresql-administration/psql-commands/) command to connect to another database.(eg. to switch from postgres=# to chinook=# we type: \c chinook)

The [\i]() command to initialize (install) our chinook sql file. ( eg. \i Chinook_PostgreSql.sql).

 - (psql -d chinook) to connect to connect to the database we have created.

 The [\dt]() command allow us display tables in our database.

Basic PostgreSql CLI Commands:

- SELECT - extracts data from a database
- UPDATE - updates data in a database
- DELETE - deletes data from a database
- INSERT INTO - inserts new data into a database
- CREATE DATABASE - creates a new database

To find out more about SQL please check out  this Quick Reference from [W3Schools](https://www.w3schools.com/sql/sql_quickref.asp)

## Using PostgreSql with Python3.

Installing a Python package and data adapter called [psycopg2](https://pypi.org/project/psycopg2/¦¦¦).

- pip3 install psycopg2


---

Happy coding!
