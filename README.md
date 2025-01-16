# Python RecursionError Example

This repository demonstrates a common error in recursive functions in Python: the `RecursionError`.  The `factorial.py` file contains a simple factorial function that will correctly calculate the factorial of non-negative integers, but it will raise a `RecursionError` if given a negative input. The `factorial_solution.py` file demonstrates how to fix this.

The `RecursionError` is caused by the recursive calls to the factorial function exceeding the maximum allowed recursion depth. The solution involves adding a base case to handle negative numbers, preventing infinite recursion.