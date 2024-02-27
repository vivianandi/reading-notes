# Object-Oriented Programming, HTML Tables

## Domain Modeling
**1. Explain why we need domain modeling.**
A domain model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem and it can verify and validate the understanding of a specific problem among various stakeholders.

## HTML Table Basics
**1. Why should tables not be used for page layouts?**
- Layout tables reduce accessibility for visually impaired users
- Tables produce tag soup
- Tables are not automatically responsive

**2. List and describe 3 different semantic HTML elements used in an HTML `<table>`.**
`<th>` table header, `<tr>` table row, `<td>` table data

## Introducing Constructors
**1. What is a constructor and what are some advantages to using it?**
- A constructor is a special method or function that is called automatically when an object is created from a class
- A constructor is just a function called using the new keyword. 
- When you call a constructor, it will:
  - create a new object
  - bind this to the new object, so you can refer to this in your constructor code
  - run the code in the constructor
  - return the new object.

**2. How does the term `this` differ when used in an object literal versus when used in a constructor?**
In an object literal, this refers to the object itself, while in a constructor, it points to the instance being created, enabling the initialization of instance-specific properties and methods.

## Object Prototypes Using A Constructor
**1. Explain prototypes and inheritance via an analogy from your previous work experience.**
**NOTE: This is a very common front end developer interview question**
A firm's standardized methodologies and best practices can be thought of as a prototype. When a new project team is formed, it inherits the foundational knowledge and best practices from the firm's centralized expertise, akin to an object inheriting characteristics from its prototype. This inheritance fosters consistency across projects while allowing each team to adapt and specialize its approach based on the unique requirements of the client's problem, ensuring a balance between standardized practices and tailored solutions.

## Resources
[HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)
