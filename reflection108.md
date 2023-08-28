# Operators and Loops

## Expressions in JavaScript

An expression in JavaScript is a piece of code that produces a value. It can range from a simple variable or constant value to more complex combinations involving function calls and mathematical calculations. Expressions are evaluated to yield a value, and they are an essential part of building dynamic and functional code.

## Using Loops in Code

Loops in JavaScript allow us to repeat a set of instructions multiple times, making it possible to automate repetitive tasks and write more efficient code. There are different types of loops in JavaScript, such as `for` loops and `while` loops, each serving specific purposes for different scenarios. While loops, continue as long as the argument is true. For loops continue during the condition in the header remains true.

## Execution of a For Loop

A `for` loop in JavaScript consists of an initialization, a condition, and an iteration statement. The loop continues executing as long as the condition specified in the loop header evaluates to `true`. Once the condition becomes `false`, the loop terminates, and the program proceeds with the code after the loop.

```javascript
for (let i = 0; i < 5; i++) {
    console.log(i); // This code will execute 5 times (i = 0 to 4)
}
