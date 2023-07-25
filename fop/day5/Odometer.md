# Odometer

* What is the most important component of the Odometer?
* The reading!

$0018991$

$9999999$
$0000000$


* We are going to work with a very special and weird Odometer.

* The digits in the odometer reading should be in strictly ascending order.

$1122$ [no]
$1039$ [no]

$5789$ [yes]

## Now some more interesting questions

* What is the next odometer reading for:

$145 \implies 146 \implies 147 \implies 148 \implies 149 \implies 156 \implies 157 \implies 158 \implies 159 \implies 167 \implies 168 \implies 169 \implies 178 \implies 179 \implies 189 \implies 234$

* What is the previous odometer reading for:

$1239 \implies 1238 \implies 1237 \implies 1236 \implies 1235 \implies 1234 \implies 6789$

* What is the smallest odometer reading for an odometer of 6 digits?

$123456$

* What is the largest odometer reading for an odometer of 3 digits?

$789$

* If we want to operate this odometer digitally, we are interested in some functions.

* What could they be?

1. Are the digits in strictly ascending order. 
public static boolean isAscending(int reading)
1. WHat is the next reading?
public static int nextReading(int reading)
1. WHat is the previous reading?
public static int prevReading(int reading)
1. What is the reading k readings after the current reading?
public static int nextKthReading(int reading, int k)
1. What is the reading k readings before the current reading?
public static int prevKthReading(int reading, int k)
1. What is the distance between two readings of the odometer?
123 <\implies 146 
14
Is this distance going to be large or small: 123 \implies 789 is the largest possible distance measurable by a 3-digit odometer
789 \implies 123 is exactly 1
public static int distanceBetween(int start, int end)
