# Subtle Null Handling Bug in JavaScript Addition Function

This repository demonstrates a common yet subtle bug in JavaScript related to null value handling in a simple addition function. The bug is not immediately obvious, but can lead to unexpected behavior in larger applications.

## Bug Description

The `foo` function adds two numbers, and returns 0 if either of the arguments are `null`. While seemingly straightforward, the behaviour of returning 0 for null input might cause confusion or lead to unexpected behavior if not handled carefully. Depending on the context, the best practice may be to throw an error instead, or utilize a different method of handling null values.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` and run it in your preferred JavaScript environment.
3. Observe the output, paying attention to the results when null values are passed as arguments.

## Solution

The provided solution in `bugSolution.js` offers an approach to improve handling of null values to prevent unexpected outcomes. The solution implements error handling and clarifies the function's intent.

## License

MIT