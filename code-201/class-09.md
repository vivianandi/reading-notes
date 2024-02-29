# Forms and JS Events

## HTML Forms
**Why are forms so important in web development?**
They facilitate user interaction, data collection, and communication between users and websites. 

**When designing a form, what are some key things to keep in mind when it comes to user experience?**
Clarity, simplicity, error

**List 5 form elements and explain their importance.**
- `<form>` - is essential for handling data collection and user interactions
- `<label>` -  it associates text labels with form elements, providing a clear and accessible description of what each input field represents
- `<input>` - handles different input scenarios, making it a fundamental building block for interactive forms
- `<textarea>` - essential for capturing multi-line text input, such as comments, messages, or detailed information
- `<button>` - serves as a trigger for form submission or other interactive actions

## Learn JS
**How would you describe events to a non-technical friend?**
Actions or occurrences that happen on a webpage, such as a button being clicked, a key on the keyboard being pressed, or the page finishing loading.

**When using the addEventListener() method, what 2 arguments will you need to provide?**
- The first argument is the type of event you want to listen for, such as 'click', 'mouseover', or 'keydown'.
- The second argument is the function (or callback) that should be executed when the specified event occurs.

**Describe the event object. Why is the target within the event object useful?**
The event object is a JavaScript object that contains information about the event that occurred -> the target property is useful because it refers to the element on which the event was originally triggered.

**What is the difference between event bubbling and event capturing?**
- Event Bubbling: This is the default behavior where the event starts from the target element and bubbles up through its ancestors. It starts from the innermost element and goes up to the outermost element.

- Event Capturing: In this phase, the event travels from the outermost element down to the target element. It is less commonly used but can be explicitly set using the addEventListener method with the third parameter as true.

## Resources
[HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)
[Event Reference and listings](https://developer.mozilla.org/en-US/docs/Web/Events)
