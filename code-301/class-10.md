# In memory storage

## [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

**What is a ‘call’?**
- A 'call' refers to the invocation of a function in a program
  - when a function is called, it is placed on top of the call stack and executed

**How many ‘calls’ can happen at once?**
- In JavaScript, only one call can happen at a time due to its single-threaded nature -> the call stack processes function calls one at a time, from top to bottom

**What does LIFO mean?**
- LIFO stands for Last In, First Out -> it's a principle used in data structures where the last item added to a stack is the first one to be removed
  - In the context of the call stack, the last function called is the first one to be executed and removed from the stack

**Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**
|       |
|_______|  thirdFunction()   <-- Top of the stack
|       |
|_______|  secondFunction()
|       |
|_______|  firstFunction()
|_______|  main()


**What causes a Stack Overflow?**
- A Stack Overflow occurs when there is a recursive function (a function that calls itself) without an exit condition -> this leads to an infinite loop of function calls, exhausting the available stack memory and resulting in a runtime error

## [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c?gi=5eb3a5370c5b)

**What is a ‘reference error’?**
- Occurs when trying to use a variable that is not yet declared
- Example: `console.log(foo) // Uncaught ReferenceError: foo is not defined`

**What is a ‘syntax error’?**
- Occurs when there is a violation of the language syntax rules
- Example: `JSON.parse( {'foo': 'bar'} ) // Uncaught SyntaxError: Unexpected token o in JSON at position 1`

**What is a ‘range error’?**
- Occurs when manipulating an object with an invalid length
Example: `var foo= []; foo.length = foo.length -1 // Uncaught RangeError: Invalid array length`

**What is a ‘type error’?**
- Occurs when types (e.g., number, string) are incompatible
- Example: `var foo = {}; foo.bar.baz // Uncaught TypeError: Cannot read property 'baz' of undefined`

**What is a breakpoint?**
- A point in the code where execution will pause, allowing inspection of variables and flow control

**What does the word ‘debugger’ do in your code?**
- Introduces a pause in code execution at a specified point, enabling the developer to inspect the program state and variables at that moment

## Resources
[JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)