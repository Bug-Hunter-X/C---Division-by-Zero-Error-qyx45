# C++ Division by Zero Bug
This repository demonstrates a common C++ error: division by zero. The `bug.cpp` file contains code that attempts to divide by zero, resulting in undefined behavior.  The `bugSolution.cpp` file shows how to prevent this error by adding a check to avoid dividing by zero.

## How to reproduce the bug
1. Compile `bug.cpp` using a C++ compiler (e.g., g++).
2. Run the compiled executable.
3. Observe the undefined behavior (likely a crash).

## Solution
The solution involves adding a check to ensure that the denominator is not zero before performing the division. The corrected code is provided in `bugSolution.cpp`.