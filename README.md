# Off-by-one Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The error arises from using the `<=` operator instead of `<` in the loop condition, resulting in an `ArrayIndexOutOfBoundsException`.

The `BuggyArray.java` file contains the erroneous code, while `FixedArray.java` provides the corrected version. The README provides a clear explanation of the issue and how it can be resolved.