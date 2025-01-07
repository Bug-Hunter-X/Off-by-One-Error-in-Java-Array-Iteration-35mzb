# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array. The `BuggyArrayIteration.java` file contains the erroneous code, which attempts to access an array element beyond its bounds.  The `FixedArrayIteration.java` file provides the corrected code.

The off-by-one error is a frequent source of bugs in programming.  It arises when a loop's termination condition is incorrectly set, causing an array element to be accessed outside the valid index range (0 to length - 1).

Understanding and avoiding these errors are crucial for writing robust and reliable Java code.