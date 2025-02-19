# Division by Zero Error in C
This repository demonstrates a common runtime error in C: division by zero. The `bug.c` file contains the erroneous code, while `bugSolution.c` provides a corrected version.

## Problem
The provided C code attempts to divide an integer by zero, leading to undefined behavior. This typically results in a program crash or unpredictable results.

## Solution
The solution involves adding input validation to check if the divisor is zero before performing the division. If the divisor is zero, an appropriate error message is displayed, preventing the division by zero error. 