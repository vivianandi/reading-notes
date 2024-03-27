# Putting it all together

[React Docs - Thinking in React](https://react.dev/learn/thinking-in-react)
- What is the single responsibility principle and how does it apply to components?
The Single Responsibility Principle (SRP) states that a component should ideally only have one reason to change. In React, this means each component should ideally handle only one specific aspect or functionality of the user interface.

- What does it mean to build a ‘static’ version of your application?
Building a 'static' version of your application means creating a version of your UI that doesn't interact with any data or user input. It focuses solely on the visual representation of the components.

- Once you have a static application, what do you need to add?
Once you have a static application, you need to add interactivity to make it dynamic. This involves adding state and handling user input to update the UI accordingly.

- What are the three questions you can ask to determine if something is state?
The three questions to determine if something is state are:
Is it passed in from a parent component via props? If so, it probably isn't state.
Does it remain unchanged over time? If so, it probably isn't state.
Can you compute it based on any other state or props in your component? If so, it probably isn't state.

- How can you identify where state needs to live?
You can identify where state needs to live by considering which component needs to change it and which components need to render it. State should live in the component that needs to change it, and any components that rely on that state should be passed it via props.

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)
- What is a “higher-order function”?
A "higher-order function" is a function that either takes another function as an argument or returns a function as its result.

- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
Line 2 of the greaterThan function checks if the argument passed to the returned function is greater than the provided number (threshold). It defines a new function (inner function) that takes a single argument (number) and returns true if the number is greater than the threshold, and false otherwise.

- Explain how either map or reduce operates, with regards to higher-order functions.
Both map and reduce are higher-order functions in JavaScript. Map transforms each element of an array by applying a function to it and returns a new array containing the transformed elements. Reduce iterates over an array, accumulating a single value based on the elements of the array and the logic defined in the provided function. It returns a single value as the result of the accumulation process.


