# Haskell Undefined Value Bug

This repository demonstrates a common error in Haskell: attempting to use an undefined value in a computation. The `undefined` value represents a computation that has not been given a value. Attempting to use it in an arithmetic operation or any other function that requires a concrete value will result in a runtime exception.

## Bug

The `bug.hs` file contains the problematic code.  It tries to add 1 to `undefined`, which leads to a runtime error.

## Solution

The `bugSolution.hs` file demonstrates how to fix this by providing a defined value for `x`.  Error handling techniques, such as pattern matching or the `Maybe` type, can be used to deal with potential undefined values in more complex cases.