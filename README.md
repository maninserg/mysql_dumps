# mysql_dumps

**About:** Dumps from MySQL

<hr>

**Description:** Different dumps of MySQL

List of dumps:
  - clone_instagram_database.sql -- simplified clone of an instagram's database. This is a full logical copy of datebase for PostgreSQL in https://github.com/maninserg/postgresql_dumps;

<hr>

<b>Reloading dumps for Linux*:</b>

1. Clone the repository (or download the zip file and extract it):

    $ `git clone git@github.com:maninserg/mysql_dumps.git`

2. Go to the directory of the program:
   
    $ `cd <your name of directory with mysql dumps>`

    **Reloading from shell**

        3. Create database:
   
            $ sudo mysqladmin create name_database
    
        4. Load the dump file:

            $ sudo mysql name_database < name_dump_file
    
      **OR Reloading from mysql**

        3. Enter to mysql:

            $ sudo mysql

        4. Use the following command:
            
            mysql> CREATE DATABASE name_database;
    
            mysql> USE name_database;
    
            mysql> source name_name_dump_file
    
<i>*The installation for MacOS or Windows can be other</i>

<hr>

**Diagrams of databases:**
