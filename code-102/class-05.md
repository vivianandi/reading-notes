# Read: 05 - Design web pages with CSS

**CSS (Cascading Style Sheets)** - a language for specifying how documents are presented to users — how they are styled, laid out, etc.
- CSS is a rule-based language — you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page

**External CSS**
Defined within the <link> element, inside the <head> section of an HTML page:
`<link rel="stylesheet" href="mystyle.css">`
- Must be saved with a .css extension
- The external .css file should not contain any HTML tags

**Internal CSS**
Used if one single HTML page has a unique style
- Defined inside the <style> element, inside the head section

**Inline CSS**
Used to apply a unique style for a single element
`<h1 style="color:blue;text-align:center;">This is a heading</h1>`

**Selector**
Elements to Style
- The "what" to style

**Code block**
What is inside the brackets
- The "where"

## Q&A
**1. What is the purpose of CSS?**
The purpose of CSS is to separate the structure of a web page (HTML) from its presentation, allowing developers to control the layout, colors, fonts, and other visual aspects of a website

**2. What are the three ways to insert CSS into your project?**
- **External CSS:** You can create a separate CSS file and link it to your HTML document using the <link> element in the <head> section.
`<head>`
`<link rel="stylesheet" type="text/css" href="styles.css">`
`</head>`

- **Internal/Embedded CSS:** You can include CSS within the HTML document using the <style> element in the <head> section.
`<head>` 
`<style>`
`p {`
  `color: blue;` 
  `}` 
`</style>` 
`</head>` 
`<body> <p>This is a blue paragraph.</p> </body>`

- **Inline CSS:** You can apply styles directly within the HTML tags using the style attribute. 
`html <p style="color: red;">This is a red paragraph.</p>`

**3. Write an example of a CSS rule that would give all <p> elements red text.**
`p {
   color: red;
}`

## References
[CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)