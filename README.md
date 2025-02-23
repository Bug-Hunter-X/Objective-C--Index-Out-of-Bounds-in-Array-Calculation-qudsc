# Objective-C Index Out of Bounds Bug

This repository demonstrates a common Objective-C bug: an index out of bounds error when accessing elements in an array. The `calculateSum:` method in `MyClass` fails to handle cases where the input array is empty or the loop index exceeds the valid range of indices. This can result in a runtime crash.

The `bug.m` file contains the erroneous code. The solution, which adds robust error handling, is provided in `bugSolution.m`.

## How to reproduce
1. Clone this repository.
2. Compile and run the code (with either the `bug.m` or `bugSolution.m` file). Note the difference in behavior.

## Solution
The solution includes checks to ensure the array is not empty before attempting to access elements and it uses a `for` loop to iterate through elements safely.