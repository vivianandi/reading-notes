# State and Props

[React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
Render

- What is the very first thing to happen in the lifecycle of React?
Mount

- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
The order of lifecycle methods is: constructor, render, componentDidMount, React Updates, componentWillUnmount.

- What does componentDidMount do?
componentDidMount is invoked immediately after a component is mounted or inserted into the DOM. It is often used to perform tasks such as fetching data from an external source or initializing third-party libraries

[React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)
- What types of things can you pass in the props?
Props can accept various types of data, including strings, numbers, arrays, objects, functions, and React elements

- What is the big difference between props and state?
The major difference between props and state is that props are passed from parent to child components, while state is managed within a component and can be updated internally

- When do we re-render our application?
Our application re-renders when there are changes in either props or state

- What are some examples of things that we could store in state?
Examples of things stored in state include form input values, toggle states for UI components, fetched data from an API, and any data that may change over time within a component

# Resources
[React Docs - State and Lifecycle](https://legacy.reactjs.org/docs/state-and-lifecycle.html)
[React Docs - handling events](https://legacy.reactjs.org/docs/handling-events.html)
[React Tutorial through ‘Developer Tools’](https://react.dev/learn/tutorial-tic-tac-toe)
[React Bootstrap Documentation](https://react-bootstrap.github.io/)
[Boootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
[Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)
[Netlify](https://www.netlify.com/)