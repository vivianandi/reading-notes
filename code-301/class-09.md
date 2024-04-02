# Functional Programming

## [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

**What is functional programming?**
- Functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions and emphasizes immutable data and avoiding changing state

**What is a pure function and how do we know if something is a pure function?**
- A pure function is a function that:
  - Returns the same result if given the same arguments (deterministic)
  - Does not cause any observable side effects
- We can determine if a function is pure by checking if it meets these criteria

**What are the benefits of a pure function?**
- Pure functions are easier to reason about and test
- They are predictable and stable, always returning the same result for the same input
- They promote code maintainability and modularity

**What is immutability?**
- Immutability refers to the property of data that once created, cannot be changed -> if you want to modify an immutable object, you create a new object with the new value rather than changing the existing one

**What is Referential transparency?**
- Referential transparency is a property of pure functions -> it means that if a function consistently yields the same result for the same input, it can be replaced with its result without changing the program's behavior
  - This property enables optimization techniques like memoization

[Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

**What is a module?**
- A module is a reusable piece of code that encapsulates related functionality, such as variables, functions, and classes -> it helps organize code into logical units and promotes modularity and reusability

**What does the word ‘require’ do?**
- The `require` keyword in Node.js is used to import modules -> it loads the specified module and returns its exports

**How do we bring another module into the file the we are working in?**
- To bring another module into the file we are working in, we use the require function followed by the path to the module file
  - For example: `const myModule = require('./myModule')`

**What do we have to do to make a module available?**
- To make a module available, we need to define its functionality and export it using the `module.exports` or `exports` object
  - This makes the functions, variables, or classes defined in the module accessible to other modules that `require` it.