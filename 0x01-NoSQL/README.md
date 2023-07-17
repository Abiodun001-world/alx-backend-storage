# 0x01-NoSQL

This is a project on NoSQL databases as part of the ALX Africa Holberton School curriculum.

## Description

The goal of this project is to introduce you to NoSQL databases, specifically MongoDB. You will learn the concepts and principles of NoSQL, the differences between SQL and NoSQL, and how to work with MongoDB using Python.

## Learning Objectives

By the end of this project, you should be able to explain the following concepts without the help of Google:

- What NoSQL means
- The difference between SQL and NoSQL
- ACID properties
- Document storage in NoSQL
- Types of NoSQL databases
- Benefits of using a NoSQL database
- How to query information from a NoSQL database
- How to insert, update, and delete information in a NoSQL database
- How to use MongoDB

## Files

The project contains the following files:

- `0-list_databases`: A MongoDB command file that lists all databases in the MongoDB server.
- `README.md`: The project readme file.

## Requirements

### MongoDB Command File

- All files will be interpreted/compiled on Ubuntu 18.04 LTS using MongoDB version 4.2.
- All files should end with a new line.
- The first line of all files should be a comment: `// my comment`.
- The length of your files will be tested using `wc`.

### Python Scripts

- All files will be interpreted/compiled on Ubuntu 18.04 LTS using `python3` version 3.7 and `PyMongo` version 3.10.
- All files should end with a new line.
- The first line of all files should be exactly `#!/usr/bin/env python3`.
- A `README.md` file, at the root of the project folder, is mandatory.
- Your code should use the `pycodestyle` style (version 2.5.*).
- The length of your files will be tested using `wc`.
- All your modules should have documentation (run `python3 -c 'print(__import__("my_module").__doc__)'`).
- All your functions should have documentation (run `python3 -c 'print(__import__("my_module").my_function.__doc__)'`).
- Your code should not be executed when imported (by using `if __name__ == "__main__":`).

### Resources

- NoSQL Databases Explained
- What is NoSQL?
- MongoDB with Python Crash Course - Tutorial for Beginners
- MongoDB Tutorial 2: Insert, Update, Remove, Query
- Aggregation
- Introduction to MongoDB and Python
- mongo Shell Methods
- The mongo Shell

### Installation

To install MongoDB 4.2 on Ubuntu 18.04, follow these steps:

```bash
$ wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | apt-key add -
$ echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.2 multiverse" > /etc/apt/sources.list.d/mongodb-org-4.2.list
$ sudo apt-get update
$ sudo apt-get install -y mongodb-org
...
$ sudo service mongod status
mongod start/running, process 3627
$ mongo --version
MongoDB shell version v4.2.8
git version: 43d25964249164d76d5e04dd6cf38f6111e21f5f
OpenSSL version: OpenSSL 1.1.1 11 Sep 2018
allocator: tcmalloc
modules: none
build environment:
    distmod: ubuntu1804
    distarch: x86_64
    target_arch: x86_64
$  
$ pip3 install pymongo
$ python3
>>> import pymongo
>>> pymongo.__version__
'3.10.1'
```

If you encounter the error "Data directory /data/db not found, terminating" or have issues with document creation, please run the following command:

```bash
$ sudo mkdir -p /data/db
```

## Usage

Follow the instructions in each script file to complete the tasks. Make sure to test your code and ensure it behaves as expected.

## Authors

- Emmanuel Turlay, Staff Software Engineer at Cruise
- Guillaume, CTO at Holberton School

**Good luck with your project!**
