# Ranking products
You have been given a comma-separated list of products and their ratings on a scale of 100 by a research firm you employed. However, they've given you the data in the order in which they did research, so it's not guaranteed to be in an order useful to make business decisions. The good thing is that all the data is well-formatted in the following format:
```
product1, 85
product2, 53
product3, 85
product4, 23
...
```
Your task is to produce a ranked list of products that looks like this:
```
1, product1
1, product3
3, product2
4, product4
```
Note that you need to give product1 and product3 the same rank, and this pushes product2 to rank 3 in our system.

Write a java function that can help you. These are the things to consider:

1. You need to read from a file and write to a file
1. You need a robust data structure to represent the input once read fromt he file.
1. You need an efficient algorithm that produces a rank list without traversing the list of products too many times.

Everything else is up to you. You are required to submit a single .java file.
