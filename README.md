This repository contains a Hack program demonstrating a stack overflow error caused by unbounded recursion in a factorial function. The `foo` function recursively calculates the factorial, but without a base case for negative inputs, it leads to infinite recursion, exceeding the stack limit. The solution modifies the function to handle negative inputs gracefully.