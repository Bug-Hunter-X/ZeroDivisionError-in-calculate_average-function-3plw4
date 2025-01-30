# Python Code Bug: ZeroDivisionError in calculate_average Function

This repository demonstrates a common Python coding error: a `ZeroDivisionError` that occurs when attempting to calculate the average of an empty list.  The `calculate_average` function originally lacked proper handling for this edge case. The solution provided addresses this issue by explicitly checking for an empty list and returning 0 in that scenario.

## How to Reproduce the Bug
1. Clone this repository.
2. Run `bug.py`.  Observe that it raises a `ZeroDivisionError` when the empty list is provided.

## Solution
The `bugSolution.py` file provides a corrected version of the function. It checks if the input list is empty and returns 0 in that case, preventing the `ZeroDivisionError`.

## Learning Points
* Always consider edge cases when writing functions, such as empty lists, null values or zero values as divisors.
* Robust error handling is crucial for creating stable and reliable code.
* Proper input validation is key to preventing common runtime exceptions.