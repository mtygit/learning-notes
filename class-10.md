## Error Handling & Debugging

Debugging is the process of finding errors. It involves a process of deduction. Using console wisely and narrowing down the potential error location and then find the exact errors. JavaScript has 7 different types of errors. Each reports its own error object, which will show the line number and gives a description of the error.

- Error: generic error
- SyntaxError: syntax has not been followed
- ReferenceError: tried to reference a variable that is not declared/within scope
- TypeError: and unexpected data type that cannot be coerced
- RangeError: numbers not in acceptable range
- URIError: encodeURI(), decodeURI(), and similar methods used incorrectly
- EvalError: eval() function used incorrectly

Debugging workflow:
1. set breakpoints and check the variables around them
2. break down parts of the code to test smaller pieces 
3. check the number of parameters for a function, or the number of items in an array

[<==Back](README.md)