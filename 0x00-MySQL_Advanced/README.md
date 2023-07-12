# 0x00-MySQL_Advanced

This directory contains the project "MySQL Advanced" assigned by ALX Africa, following the curriculum of Holberton School.

## Description
The "MySQL Advanced" project focuses on advanced SQL concepts and their implementation in MySQL. It covers topics such as creating tables with constraints, optimizing queries with indexes, using stored procedures, functions, views, and triggers in MySQL.

## Concepts
Before starting the project, make sure you understand the following concept:
- Advanced SQL

## Resources
To successfully complete this project, you should read or watch the following resources:
- [MySQL cheatsheet](https://devhints.io/mysql)
- [MySQL Performance: How To Leverage MySQL Database Indexing](https://www.alexhadik.com/blog/2018/5/21/mysql-performance-how-to-leverage-mysql-database-indexing)
- [Stored Procedure](https://dev.mysql.com/doc/refman/5.7/en/stored-programs-defining.html)
- [Triggers](https://dev.mysql.com/doc/refman/5.7/en/triggers.html)
- [Views](https://dev.mysql.com/doc/refman/5.7/en/views.html)
- [Functions and Operators](https://dev.mysql.com/doc/refman/5.7/en/functions.html)
- [Trigger Syntax and Examples](https://dev.mysql.com/doc/refman/5.7/en/trigger-syntax.html)
- [CREATE TABLE Statement](https://dev.mysql.com/doc/refman/5.7/en/create-table.html)
- [CREATE PROCEDURE and CREATE FUNCTION Statements](https://dev.mysql.com/doc/refman/5.7/en/create-procedure.html)
- [CREATE INDEX Statement](https://dev.mysql.com/doc/refman/5.7/en/create-index.html)
- [CREATE VIEW Statement](https://dev.mysql.com/doc/refman/5.7/en/create-view.html)

## Learning Objectives
By the end of this project, you should be able to explain the following topics without using external resources:

- How to create tables with constraints
- How to optimize queries by adding indexes
- What are stored procedures and functions in MySQL and how to implement them
- What are views in MySQL and how to implement them
- What are triggers in MySQL and how to implement them

## Requirements
- All your files will be executed on Ubuntu 18.04 LTS using MySQL 5.7 (version 5.7.30)
- All your files should end with a new line
- All your SQL queries should have a comment just before (i.e. syntax above)
- All your files should start by a comment describing the task
- All SQL keywords should be in uppercase (SELECT, WHERE...)
- The length of your files will be tested using `wc`

## Usage
To run the MySQL container and execute the SQL files, follow these steps:

1. Use "container-on-demand" to run MySQL.
2. Ask for the container with Ubuntu 18.04 - Python 3.7.
3. Connect via SSH or WebTerminal.
4. Start the MySQL service in the container:
   ```
   $ service mysql start
     * MySQL Community Server 5.7.30 is started
   ```
5. Import the necessary SQL dump:
   ```
   $ echo "CREATE DATABASE hbtn_0d_tvshows;" | mysql -uroot -p
   Enter password:
   $ curl "https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/274/hbtn_0d_tvshows.sql" -s | mysql -uroot -p hbtn_0d_tvshows
   Enter password:
   ```
   The above commands create a database `hbtn_0d_tvshows` and import a SQL dump into it.

Make sure to replace `your_file.sql` with the actual name of your SQL file.

## Credits
This project is part of the curriculum by Holberton School and is assigned by ALX Africa.
