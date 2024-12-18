# Unexpected Calculation Result in Swift Function

This repository demonstrates a subtle bug in a Swift function that calculates the area of a rectangle. The issue arises from an implicit type conversion that leads to an unexpected result.

## Bug Description

The `calculateArea` function calculates the area of a rectangle given its width and height. However, due to an implicit type conversion, it returns an incorrect result when dealing with certain input values.

## Bug Reproduction

1. Clone this repository.
2. Open `bug.swift`.
3. Run the code. Observe that the calculated area is not what is expected.

## Solution

The solution is presented in `bugSolution.swift`. It explicitly defines types for parameters to prevent implicit conversion and ensure accurate calculations.

## Additional notes

This bug highlights the importance of being attentive to type safety in Swift. By explicitly defining the types of function parameters, we can avoid such implicit conversion issues and ensure the correctness of our calculations.