# The Collatz conjecture
The Collatz conjecture is a popular unsolved problem in recreational mathematics. Mathematician Lothar Collatz discovered that by performing one of two actions repeatedly to any integer, namely:

* If the integer is even, divide it by 2
* If the integer is odd, multiply it by 3 and add 1

The sequence thus created always concludes in $\ldots, 4, 2, 1.$

For instance, take $23$. It results in the sequence $23 \implies 70 \implies 35 \implies 106 \implies 53 \implies 160 \implies 80 \implies 40 \implies 20 \implies 10 \implies 5 \implies 16 \implies 8 \implies 4 \implies 2 \implies 1$

Write a static java function that takes an integer as input and returns a `List<Integer>` containing the Collatz sequence for that integer.

