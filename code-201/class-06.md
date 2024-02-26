# Problem Domain, Objects, and the DOM

## JavaScript Object Basics
**1. How would you describe an object to a non-technical friend you grew up with?**
An object is like a container that can hold various things, and each thing inside it has a special name or job. Imagine you have a backpack (the object), and inside it, you have different pockets (properties) for your snacks, toys, and homework. Each pocket has a specific purpose, and you can organize and access everything easily.

**2. What are some advantages to creating object literals?**
Simplicity, readability

**3. How do objects differ from arrays?**
Structure and use cases

**4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**
You need bracket notation if the property name contains special characters, starts with a number, or is a reserved keyword.

**5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using this?**
To the current instance of the Car object being created. When the Car function is used as a constructor with the new keyword, this refers to the specific instance of the object being created. The advantage of using this is that it allows you to set properties on the individual instance of the object, customizing it with specific values.

## Introduction To The DOM
**1. What is the DOM?**
The DOM, or Document Object Model, is a programming interface for web documents. The DOM provides a way for programs (like JavaScript) to manipulate the structure, style, and content of web documents dynamically.

**2. Briefly describe the relationship between the DOM and JavaScript.**
JavaScript interacts with HTML documents through the DOM. When a web page is loaded, the browser creates a DOM representation of the page. 

## Resources
- [Understanding the problem domain is the hardest part of programming](https://simpleprogrammer.com/solving-problems-breaking-it-down/)
- [What’s the difference between primitive values and object references in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)