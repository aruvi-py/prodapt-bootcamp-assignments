## The Point class
A point in 2D space is represented by a pair of coordinates like so: (10.0, 2.5). Write a Java class whose instances represent a single point in 2D space. Include the method:

```
public double distanceFrom(Point other)
```

Include any other methods you find necessary.

## The Line class
A line in 2D space is represented in two equivalent ways: `y = mx + c` or `ax + by + c = 0`. Pick one way of representing it, and write a Java class whose instances represent a single line in 2D space. Include the method:

```
public double distanceFrom(Point p)
```
```
public Point intersection(Line other)
```

What do you think the `intersection` method should return when the lines are parallel? Think about it. Include any other methods you find necessary.

## The Testing class

* Write a new class called `Testing` to test the classes you've written until now.
* Create a Line to represent `y = x + 5`
* Create a Line to represent `y = 2x + 10`
* Print the distance from the origin (Point(0, 0)) to the intersection between the two lines above.
