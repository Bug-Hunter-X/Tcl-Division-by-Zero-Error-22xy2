# Tcl Division by Zero Error

This repository demonstrates a common error in Tcl: division by zero.  The `bug.tcl` file contains a procedure that does not correctly handle cases where the divisor is zero. The `bugSolution.tcl` provides a corrected version.

## Bug Description
The `badproc` procedure in `bug.tcl` attempts to divide `b` by `a`. If `a` is 0, a runtime error occurs. 

## Solution
The `bugSolution.tcl` file demonstrates how to handle the potential division-by-zero error using a conditional statement to check if the divisor is zero before performing the division.