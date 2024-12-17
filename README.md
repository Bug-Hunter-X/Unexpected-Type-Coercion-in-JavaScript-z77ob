# Unexpected Type Coercion in JavaScript

This repository demonstrates a common JavaScript bug related to type coercion.  The `myFunction` adds a number and a string, resulting in unexpected string concatenation instead of numerical addition.  The `bugSolution.js` file offers a solution to prevent this issue. 

## Bug Description

In JavaScript, when you add a number to a string, JavaScript will automatically convert the number to a string and perform string concatenation. This is known as type coercion, and it can lead to unexpected results if you are not aware of it.

## Solution

The solution involves explicitly converting the inputs to numbers before performing the addition.  This ensures that the mathematical addition is performed correctly.