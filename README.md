# Julia Function Bug
This repository demonstrates a bug in a simple Julia function that unexpectedly handles negative numbers. The function is designed to return the square of a number, but it exhibits unexpected behavior when provided with negative inputs.  The bug is addressed in the `bugSolution.jl` file.

## Bug Description
The `myfunction` function in `bug.jl` should return the square of a number, regardless of its sign. However, when a negative number is passed as an argument, the function returns the negative of the square of that number. 

## Solution
The bug is resolved in `bugSolution.jl` by correctly implementing the squaring logic to account for the sign of the input number. 
