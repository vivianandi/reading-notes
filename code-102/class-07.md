# Read: 07 - Programming with JavaScript

**Control flow** is the order in which the computer executes statements in a script
- Code is run in order from the first line in the file to the last line

**Javascript function** is a block of code designed to perform a particular task
- Executed when "something" invokes it (calls it)
- Defined with the function keyword, followed by a name, followed by parentheses `()`
  - The parentheses may include parameter names separated by commas:
`(parameter1, parameter2, ...)`
- The code to be executed, by the function, is placed inside curly brackets: `{}`
- **Example**
  - `function name(parameter1, parameter2, parameter3) {`
  `// code to be executed`
`}`

**Function Invocation**
Function code executes when triggered by:
- Event occurrence (e.g., button click)
- Invocation from JavaScript code
- Automatic (self-invoked)

**Function Return**

-  `return` statement halts function execution
- Resumes after invoking statement if called from one
- Functions often yield a return value
- **Example**
  - `function myFunction(a, b) {`
  `return a * b; // example return statement`
`}`

**Why Functions?**
- Facilitates code reuse for various purposes.
- Same code, different arguments, yields diverse results

**The `()` Operator**
- Invokes (calls) the function
- Incorrect parameters result in faulty outputs
- Without (), refers to the function object, not the result

**Local Variables**
- Variables declared inside a function are local to that function
- Accessible only within the function

## Operators

**Types of JavaScript Operators:**
- **JavaScript Assignment**
Assignment Operator (=) assigns a value to a variable

- **JavaScript Addition**
Addition Operator (+) adds numbers

- **JavaScript Multiplication**
Multiplication Operator (*) multiplies numbers

- Various types include **Arithmetic Operators** (perform operations on numbers), Assignment, Comparison, String, Logical, Bitwise, Ternary, and Type Operators

**JavaScript Assignment Operators**
Assignment operators assign values to variables
![AO](/reading-notes/code-102/img/assignmentoperators.jpg)

**JavaScript Comparison Operators**
Compare values or variables
![AO](/reading-notes/code-102/img/comparisonoperators.jpg)

**JavaScript String Comparison**
Comparison operators can be used on strings
`+` adds **(concatenates)** strings

Adding numbers returns sum; adding a number and a string returns a string

## Q&A

**1. What is `control flow`?**
The order in which the computer executes statements in a script

**2. What is a JavaScript `function?`**
A block of code designed to perform a particular task

**3. What does it mean to `invoke` - or `call` - a function?**
The code inside the function will execute when "something" invokes (calls) the function:
- When an event occurs (when a user clicks a button)
- When it is invoked (called) from JavaScript code
- Automatically (self invoked)

**4. What are the parenthesis `()` for when you define a function?**
Function parameters are listed inside the parentheses () in the function definition

## References
[Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

[Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)