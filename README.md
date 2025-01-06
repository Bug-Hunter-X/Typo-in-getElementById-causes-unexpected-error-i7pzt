# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a subtle error that can occur in HTML/JavaScript when there's a simple typo in the function used to access an element by its ID.

The `bug.html` file contains a typo in the `getElementById` function, leading to a runtime error. The `bugSolution.html` provides the correct solution.

## Bug Description

A common mistake is making a slight typo when using `document.getElementById()` to select an HTML element.  This can be very difficult to spot, especially in larger codebases.

## How to reproduce
1. Open `bug.html` in a web browser.
2. Observe the error message in the browser's developer console.

## Solution
The `bugSolution.html` file shows the corrected code with the proper use of `document.getElementById()`, preventing the error.

