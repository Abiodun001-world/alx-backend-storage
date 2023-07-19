# 0x02. Redis Basic - Back-end

## Introduction

This project aims to provide a basic understanding of Redis, a popular in-memory data structure store used as a cache, database, and message broker. Redis offers fast and efficient data storage and retrieval, making it an excellent choice for various applications, especially in a distributed environment.

## Learning Objectives

By completing this project, you will:

- Gain proficiency in using Redis for basic operations.
- Learn how to implement Redis as a simple cache.
- Familiarize yourself with Redis commands and the Redis Python client.

## Requirements

- The code should be written in Python 3.7 and will be interpreted/compiled on Ubuntu 18.04 LTS.
- All files should end with a new line, and the first line of each file must be `#!/usr/bin/env python3`.
- Follow the `pycodestyle` style (version 2.5) for maintaining code consistency.
- Include proper documentation for all modules, classes, functions, and methods following the standard Python docstring conventions.
- Use type annotations for all functions and coroutines.
- The project should have a README.md file at the root of the folder, providing essential information and instructions.

## Resources

Before starting the project, review the following resources:

1. [Redis Commands](https://redis.io/commands)
2. [Redis Python Client](https://redis-py.readthedocs.io/en/stable/)
3. [How to Use Redis With Python](https://realpython.com/python-redis/)
4. [Redis Crash Course Tutorial](https://www.youtube.com/watch?v=Hbt56gFj998)

## Installation

### Install Redis on Ubuntu 18.04

To install Redis on Ubuntu 18.04, follow these steps:

```bash
$ sudo apt-get -y install redis-server
$ pip3 install redis
$ sed -i "s/bind .*/bind 127.0.0.1/g" /etc/redis/redis.conf
```

### Use Redis in a Container

When starting a container, make sure to start the Redis server explicitly using the following command:

```bash
$ service redis-server start
```

## About the Author

Emmanuel Turlay is a Staff Software Engineer at Cruise, with vast experience in backend development and distributed systems. He is passionate about sharing knowledge and exploring new technologies to build robust and scalable solutions. Connect with Emmanuel on [LinkedIn](https://www.linkedin.com/in/emmanuelturlay/).

Let's dive into the world of Redis and discover its immense potential for your next project! If you have any questions or need assistance, feel free to reach out. Happy coding!
