# Off-by-one Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`.  The error occurs because the loop condition `i <= vec.size()` attempts to access an element beyond the valid range of indices (0 to size()-1).  This can lead to crashes or unpredictable behavior.

The `bug.cpp` file shows the erroneous code.  The `bugSolution.cpp` file provides a corrected version.