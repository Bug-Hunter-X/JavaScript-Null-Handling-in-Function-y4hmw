# JavaScript Null Handling

This repository demonstrates a common error in JavaScript related to handling null values within functions and its proposed solution.

## Description

The `bug.js` file contains a function that performs addition. However, if one or both of its inputs are null, it will return NaN. This demonstrates an issue in JavaScript where null values should always be explicitly handled to prevent unwanted behaviors such as incorrect calculations and exceptions.

## Solution

The `bugSolution.js` file demonstrates a fix that explicitly handles null inputs, returning 0 if null is found. This approach prevents potential errors and produces more predictable behavior.

## How to Run

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in a text editor.
3. Run the code in your preferred JavaScript environment (Node.js, browser console, etc.).