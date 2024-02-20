# Read: Class 01
 
### How the Web Works
**Clients:** Devices (e.g., computer, phone) connected to the internet with web-accessing software
**Servers:** Store webpages; provide requested content to clients for display in web browsers

### Additional Components
**Internet Connection:** Enables data exchange between client and server
**TCP/IP:** Protocols defining internet data transmission mechanisms, similar to transport modes
**DNS (Domain Name System):** Acts as an address book, translating web addresses to IP addresses
**HTTP (Hypertext Transfer Protocol):** Application protocol for client-server communication
**Component Files:** Websites composed of HTML, CSS, JavaScript (code files) and other assets (images, documents)

### Web Process Overview
**1. Address Resolution:** Browser consults DNS for the server's real address
**2. HTTP Request:** Browser sends request to server for the website
**3. Server Response:** If approved, server sends "200 OK" and transmits website files as data packets
**4. Client Display:** Browser assembles and displays the webpage

### JavaScript 
**Javascript** is a powerful programming language for adding interactivity to websites


### Features and Versatility
**Beginner-Friendly:** Suitable for beginners; expands to advanced applications with experience
**Compact and Flexible:** Relatively small yet highly adaptable language
**Tools and Enhancements:** Various tools built on core JavaScript, including browser APIs, third-party APIs, frameworks, and libraries

### Language Basics Crash Course
**Variables:** Containers storing values; declared using `let` keyword
**Naming and Assignment:** Follow naming rules; variables are case-sensitive; assign and change values
**Data Types:** String, Number, Boolean, Array, Object
**Comments:** Text snippets ignored by the browser; use /* */ or // for single-line comments

### Javascript Q & A
**1. Compose a short poem describing how HTTP sends data between computers.**
In the computer's world, where data flies,
HTTP helps it reach the skies.
Packets zoom, like tiny cars,
Traveling fast, like shooting stars.
From your click to a webpage's call,
HTTP's the friend that delivers all.

**2. Describe how HTML, CSS, and JS files are “parsed” in the browser.**
**HTML Parsing:** The browser reads and interprets HTML files to create the document's structure, identifying elements and their relationships
**CSS Parsing:** After HTML, the browser parses CSS files, applying styles to HTML elements, altering their appearance
**JS Parsing:** Lastly, the browser parses JavaScript files, executing code that can manipulate the HTML and CSS, enabling dynamic behavior

**3. How can you find images to add to a Website?**
Search engine, stock photos

**4. How do you create a `String` vs a `Number` in JavaScript?**
**String:** Enclose characters in quotes, like `let text = "Hello";`
**Number:** Assign a numerical value without quotes, like `let number = 42;`

**5. What is a `Variable` and why are they important in JavaScript?**
Named container holding a value that holds various data types, stores and retrieves values

### HTML Q & A
**1. What is an HTML attribute?**
An HTML attribute provides additional information about an element and is always included in the opening tag, consists of a name and a value

**2. Describe the Anatomy of an HTMl element.**
**Opening Tag:** Contains the element's name
**Closing Tag:** Similar to the opening tag but with a forward slash before the element name
**Content:** The element's content, such as text or other nested elements


**3. What is the Difference between `article` and `section` element tags?**
**`article`:** Represents a self-contained piece of content with independent meaning, such as a blog post or news article

**`<section>`:** Defines a thematic grouping within a document, often used to structure content but doesn't inherently convey independent meaning

**4. What Elements does a “typical” website include?**
Header, footer, nav, main, article, aside, div

**5. How does metadata influence Search Engine Optimization?**
Metadata provides information (keywords) about the webpage's content, aiding search engines in understanding and ranking the page.

**6. How is the `meta` HTML tag used when specifying metadata?**
Name and content attributes used to provide type of metadata and content information

### MISC Q & A
**What is the first step to designing a Website?**
Planning: Understand the purpose, audience, and content -> define goals, structure, and features

**What is the most important question to answer when designing a Website?**
What is the goal 

**Why should you use an `h1` element over a `span` element to display a top level heading?**
`h1` carries semantic meaning as a top-level heading, aiding accessibility and search engine optimization

**What are the benefits of using semantic tags in our HTML?**
Claity, accessibility, SEO

**Describe 2 things that require JavaScript in the Browser?**
Form validation, dynamic content 

**How can you add JavaScript to an HTML document?**
Inline or using an external JS file