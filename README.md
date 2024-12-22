# Unexpected String Concatenation in JavaScript

This repository demonstrates a common, yet subtle, error in JavaScript: unexpected string concatenation due to its loose typing system.  The `foo` function intends to add two numbers, but because one argument is a string, JavaScript performs string concatenation instead of numerical addition.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` and run it using a JavaScript interpreter (Node.js, a browser's console, etc.).
3. Observe that the output is "12", not 3, as one might expect.

## Solution

The `bugSolution.js` file provides a corrected version using explicit type checking or coercion to ensure addition is performed correctly.
