# IndexError in Dart List Access
This repository demonstrates a common error in Dart: the `IndexError`.  The `bug.dart` file contains code that throws this error, while `bugSolution.dart` provides a corrected version.
The `IndexError` occurs when attempting to access an element of a list (or other indexed collection) using an index that is outside the valid range of indices.

## How to Reproduce
1. Clone this repository.
2. Run `bug.dart` using the Dart command line.

## Solution
The solution involves checking the index before accessing the list element to prevent the `IndexError`.  See `bugSolution.dart` for the corrected code.