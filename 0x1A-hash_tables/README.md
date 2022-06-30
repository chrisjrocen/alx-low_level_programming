# 0x1A. C - Hash tables

## Resources

1. [What is a HashTable Data Structure - Introduction to Hash Tables , Part 0](https://www.youtube.com/watch?v=MfhjkfocRR0)

1. [Hash function](https://en.wikipedia.org/wiki/Hash_function)

1. [Hash table](https://en.wikipedia.org/wiki/Hash_table)

## Learning Objectives

* What is a hash function
* What makes a good hash function
* What is a hash table, how do they work and how to use them
* What is a collision and what are the main ways of dealing with collisions in the context of a hash table
* What are the advantages and drawbacks of using hash tables
* What are the most common use cases of hash tables

## Python Dictionaries

Python dictionaries are implemented using hash tables. 

So much is actually happening when you type d = {'a': 1, 'b': 2}, but everything looks so simple for the user. If you are curious on how Python works under the hood, here is [a good blog post about how dictionaries are implemented in Python 2.7.](http://www.laurentluce.com/posts/python-dictionary-implementation/)

Note that all dictionaries are not implemented using hash tables and there is a difference between a dictionary and a hash table. [Read more here.](https://stackoverflow.com/questions/2061222/what-is-the-true-difference-between-a-dictionary-and-a-hash-table)

In PHP, hash tables are ordered. Before you continue, please take a moment to think about it: how you would implement it if you were asked to during an interview or a job. What data structures would you use? How would it work? Read [PHP Internals book - Hash table](https://www.phpinternalsbook.com/php5/hashtables/basic_structure.html)

![PHP](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/253/php.png)
