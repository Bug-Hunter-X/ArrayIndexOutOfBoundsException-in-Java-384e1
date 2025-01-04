# ArrayIndexOutOfBoundsException Bug in Java
This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that causes this exception, while `bugSolution.java` provides the corrected version.

## Bug Description
The bug arises from an off-by-one error in the loop accessing the array.  The loop iterates one element past the valid array index, causing the exception when it tries to access `arr[5]` which is out of bounds.

## Solution
The solution involves correcting the loop condition to ensure that the loop never attempts to access an element outside the array bounds.