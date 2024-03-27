# Passing Functions as Props

[React Docs - lists and keys](https://react.dev/learn#rendering-lists)
- What does .map() return?
The .map() method returns a new array populated with the results of calling a provided function on every element in the calling array.

- If I want to loop through an array and display each value in JSX, how do I do that in React?
In React, you can use the .map() method to loop through an array and render each value in JSX by enclosing the .map() method within curly braces {} and returning JSX elements.

- Each list item needs a unique ____.
Key

- What is the purpose of a key?
The purpose of a key is to help React identify which items have changed, are added, or are removed. It helps optimize the rendering process and improves performance by minimizing DOM manipulations.

[The Spread Operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
- What is the spread operator?
The spread operator (...) is a JavaScript syntax used to expand elements of an iterable (like an array or string) into places where multiple elements are expected.

- List 4 things that the spread operator can do.
Four things the spread operator can do:
Copy an array or object.
Concatenate arrays.
Merge objects.
Clone arrays and objects.

- Give an example of using the spread operator to combine two arrays.
const array1 = [1, 2, 3];
const array2 = [4, 5, 6];
const combinedArray = [...array1, ...array2];
console.log(combinedArray); // Output: [1, 2, 3, 4, 5, 6]

- Give an example of using the spread operator to add a new item to an array.
const originalArray = [1, 2, 3];
const newArray = [...originalArray, 4];
console.log(newArray); // Output: [1, 2, 3, 4]

- Give an example of using the spread operator to combine two objects into one.
const obj1 = { a: 1, b: 2 };
const obj2 = { c: 3, d: 4 };
const combinedObject = { ...obj1, ...obj2 };
console.log(combinedObject); // Output: { a: 1, b: 2, c: 3, d: 4 }

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=n-6i_WGIOKE)
- In the video, what is the first step that the developer does to pass functions between components?
The first step the developer does to pass functions between components is defining a function in the parent component.

- In your own words, what does the handleClick function do?
The handleClick function is responsible for handling click events triggered by the user. In this specific context, it toggles the state of a component between true and false.

- How can you pass a method from a parent component into a child component?
To pass a method from a parent component into a child component, you can simply pass it as a prop when rendering the child component.

- How does the child component invoke a method that was passed to it from a parent component?
The child component can invoke a method passed from a parent component by accessing it through props and then calling it like a regular function.

# Resources
[React Tutorial through ‘Declaring a Winner’](https://react.dev/learn/tutorial-tic-tac-toe)
[React Docs - Lifting State Up](https://react.dev/learn/sharing-state-between-components#lifting-state-up-by-example)