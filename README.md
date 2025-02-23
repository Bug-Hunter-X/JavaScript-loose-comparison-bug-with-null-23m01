# JavaScript Loose Comparison Bug
This code demonstrates a common error in JavaScript related to loose comparison (==) with null values.  The function `foo` is intended to return 0 if x is null, -1 if x is negative, and 1 otherwise. However, due to the use of loose comparison, the result for x = 0 is incorrect.  The bug is demonstrated and solved in the accompanying files (bug.js and bugSolution.js).