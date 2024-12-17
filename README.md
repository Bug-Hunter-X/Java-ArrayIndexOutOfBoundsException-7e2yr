# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that attempts to access an array element outside its valid index range, leading to the exception. The `bugSolution.java` file provides the corrected code.

## Bug Description
The bug arises from an off-by-one error in the loop condition. The loop iterates from 0 up to and including `arr.length`, which is one element past the end of the array. 