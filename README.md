# COBOL Subscript Out of Range Bug

This repository demonstrates a potential subscript out of range error in COBOL. The bug is related to the improper handling of array indexes within a loop. Although straightforward, this type of error can be difficult to identify in larger programs. 

The provided code shows a simple loop iterating through an array. In a more complex program, this could lead to unexpected behavior or crashes.

The solution illustrates the proper use of data structure bounds checking to prevent subscript errors.  Careful attention to bounds checking during development and testing can significantly reduce the risk of this type of run-time error. 

## Bug

The `bug.cob` file shows the COBOL code containing the potential error.  The loop iterates from 1 to 100, and this could cause an error if the table's size changes during runtime.