# Off-by-One Error in Array Iteration

This code demonstrates a common off-by-one error in Java when iterating over an array.
The error occurs because the loop condition `i <= arr.length` attempts to access an element beyond the array's valid index range (0 to arr.length -1).
This leads to an `ArrayIndexOutOfBoundsException` during runtime.
The solution provides the correct loop condition to prevent this error.