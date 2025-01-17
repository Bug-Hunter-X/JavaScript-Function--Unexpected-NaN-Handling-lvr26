# JavaScript Function: Unexpected NaN Handling

This repository demonstrates a potential bug in a JavaScript function that doesn't explicitly handle NaN (Not a Number) values.

## Bug Description

The `foo` function adds two numbers.  However, it only explicitly handles `null` values. If either input is `NaN`, the addition results in `NaN`, leading to unexpected behavior.

## Bug Solution

The solution adds an explicit check for `NaN` values using `isNaN()`, handling them appropriately.

## How to Run

1. Clone the repository.
2. Open `bug.js` to see the original code and `bugSolution.js` to see the fixed code.
3. Run the JavaScript files in a browser's console or using Node.js.

