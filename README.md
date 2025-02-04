# Uncommon HTML DOM Access Error

This repository demonstrates an uncommon error that can occur when working with the Document Object Model (DOM) in HTML using JavaScript.

The bug involves attempting to access a property that does not exist on a DOM element. This leads to a runtime error in the browser's JavaScript engine.  The solution focuses on robust error handling and ensuring that properties are checked for existence before access.

## How to Reproduce

1. Open `bug.html` in a web browser.
2. Observe the JavaScript error in the browser's developer console. 

## Solution

The `bugSolution.html` file shows how to avoid this error. This involves checking if a property exists using `hasOwnProperty()` or by checking for null or undefined before attempting to access it.