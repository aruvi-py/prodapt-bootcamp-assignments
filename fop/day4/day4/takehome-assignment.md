# The Collatz conjecture
The Collatz conjecture is a popular unsolved problem in recreational mathematics. Mathematician Lothar Collatz discovered that by performing one of two actions repeatedly to any integer, namely:

* If the integer is even, divide it by 2
* If the integer is odd, multiply it by 3 and add 1

The sequence thus created always concludes in $\ldots, 4, 2, 1.$

For instance, take $23$. It results in the sequence $23 \implies 70 \implies 35 \implies 106 \implies 53 \implies 160 \implies 80 \implies 40 \implies 20 \implies 10 \implies 5 \implies 16 \implies 8 \implies 4 \implies 2 \implies 1$

Write a static java function that takes an integer as input and returns a `List<Integer>` containing the Collatz sequence for that integer.

### CodeRunner: Pre-filled code

```
class Solution {
        public static List<Integer> collatz(int n) {
                //your code here
        }
}
```

### Test Cases
---------------
|Input | Expected output|
|------|----------------|
|`System.out.println(Solution.collatz(23));` | [23, 70, 35, 106, 53, 160, 80, 40, 20, 10, 5, 16, 8, 4, 2, 1]|
|`System.out.println(Solution.collatz(64));` | [64, 32, 16, 8, 4, 2, 1]|
|`System.out.println(Solution.collatz(100));` | [100, 50, 25, 76, 38, 19, 58, 29, 88, 44, 22, 11, 34, 17, 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1]|
|`System.out.println(Solution.collatz(4));` | [4, 2, 1]|
|`System.out.println(Solution.collatz(259));` | [259, 778, 389, 1168, 584, 292, 146, 73, 220, 110, 55, 166, 83, 250, 125, 376, 188, 94, 47, 142, 71, 214, 107, 322, 161, 484, 242, 121, 364, 182, 91, 274, 137, 412, 206, 103, 310, 155, 466, 233, 700, 350, 175, 526, 263, 790, 395, 1186, 593, 1780, 890, 445, 1336, 668, 334, 167, 502, 251, 754, 377, 1132, 566, 283, 850, 425, 1276, 638, 319, 958, 479, 1438, 719, 2158, 1079, 3238, 1619, 4858, 2429, 7288, 3644, 1822, 911, 2734, 1367, 4102, 2051, 6154, 3077, 9232, 4616, 2308, 1154, 577, 1732, 866, 433, 1300, 650, 325, 976, 488, 244, 122, 61, 184, 92, 46, 23, 70, 35, 106, 53, 160, 80, 40, 20, 10, 5, 16, 8, 4, 2, 1]
|
|`System.out.println(Solution.collatz(99));` | [99, 298, 149, 448, 224, 112, 56, 28, 14, 7, 22, 11, 34, 17, 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1]
|
|`System.out.println(Solution.collatz(123));` | [123, 370, 185, 556, 278, 139, 418, 209, 628, 314, 157, 472, 236, 118, 59, 178, 89, 268, 134, 67, 202, 101, 304, 152, 76, 38, 19, 58, 29, 88, 44, 22, 11, 34, 17, 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1]|
|`System.out.println(Solution.collatz(2));` | [2, 1]|
|`System.out.println(Solution.collatz(1));` | [1, 4, 2, 1]|
|`System.out.println(Solution.collatz(17));` | [17, 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1]|


