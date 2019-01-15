# Assignment 29

Given a 2D array, an hourglass is a selection of values shaped like this:

```
a b c
  d
e f g
```

For example, if I create an hourglass with ones within a 2D array of zeros it may look like this:

```
1 1 1 0 0 0
0 1 0 0 0 0
1 1 1 0 0 0
0 0 0 0 0 0
0 0 0 0 0 0
0 0 0 0 0 0
```

There are actually 16 hourglasses in the 6x6 2D array above. The three leftmost hourglasses at the top of the 2D array are the following:

```
1 1 1     1 1 0     1 0 0
  1         0         0
1 1 1     1 1 0     1 0 0
```

The sum of an hourglass is the sum of all the numbers within it. The sum for the hourglasses above are 7, 4, and 2, respectively.

In this problem you have to print the largest sum among all the hourglasses in the array.

### Directions

Download the starter code (`Runner.java` and `Grid.java`) and the .txt files (`grid1.txt`, `grid2.txt`, and `grid3.txt`). 
Then, add your implementation for the `largestSum()` method and complete the `Runner` class.

Read the comments of the provided methods carefully so you know what they do and how to use them.

### Test Outputs

`grid1.txt:` 13

`grid2.txt:` 19

`grid3.txt:` 52

### Grading

Please make sure you have comments for every method you create. As always, your program will be graded on its functionality according to the project specifications and proper code style.

