# JavaScript Type Coercion Bug

This repository demonstrates a common JavaScript bug related to type coercion during addition.  The `add` function is intended to add two numbers, but it unexpectedly concatenates when one operand is a string.

## Bug

The `bug.js` file contains the erroneous code.  The `console.log` statement shows that adding a number and a string results in string concatenation rather than numerical addition.

## Solution

The `bugSolution.js` file provides a corrected version of the function, explicitly converting both arguments to numbers before addition. This prevents unexpected type coercion and ensures accurate numerical results.

## How to reproduce:

1. Clone this repository.
2. Navigate to the directory.
3. Run `node bug.js` to see the incorrect output.
4. Run `node bugSolution.js` to see the corrected output.