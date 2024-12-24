# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common error in Java programming: the `ArrayIndexOutOfBoundsException`. The code attempts to access an array element using an index that is out of bounds, leading to a runtime exception.

## Bug Description

The `Bug.java` file contains code that iterates through an array using a `for` loop. The loop condition `i <= arr.length` is incorrect; it should be `i < arr.length`.  This causes the loop to attempt to access the element at index 5 (the array length), which does not exist, resulting in an `ArrayIndexOutOfBoundsException`.

## Solution

The `BugSolution.java` file provides a corrected version of the code with the loop condition fixed. The corrected condition `i < arr.length` ensures that the loop only iterates through valid indices.