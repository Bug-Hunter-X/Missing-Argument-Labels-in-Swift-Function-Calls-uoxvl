# Missing Argument Labels in Swift Function Calls

This repository demonstrates a common Swift error related to missing argument labels in function calls.

Swift's type system is strong, and it enforces the use of argument labels for clarity and readability. Forgetting to include the argument label when calling a function with multiple parameters will result in a compile-time error.

The `bug.swift` file contains code showcasing the error, and `bugSolution.swift` provides a corrected version.

## How to Reproduce

1. Clone this repository.
2. Open `bug.swift` in Xcode.
3. Attempt to compile and run the code. You'll see a compiler error indicating missing argument labels.

## Solution

The solution is simple: always include argument labels when calling the function.  Refer to `bugSolution.swift` for the corrected code.