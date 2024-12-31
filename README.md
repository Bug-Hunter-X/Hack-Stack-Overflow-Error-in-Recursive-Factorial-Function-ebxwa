# Hack Stack Overflow Bug

This repository demonstrates a stack overflow error in Hack caused by unbounded recursion in a factorial function and its iterative solution.

The `bug.hack` file contains the buggy code, which uses recursion without a base case that handles sufficiently large inputs. The `bugSolution.hack` file contains the corrected code which uses iteration to avoid stack overflow errors.  

## How to reproduce the error

1. Compile and run `bug.hack`
2. Observe the stack overflow error (for large enough input values). 

## Solution

The solution utilizes an iterative approach instead of recursion, eliminating the risk of a stack overflow.