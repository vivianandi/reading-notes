# Local Storage and How To Use It On Websites

## [Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)
**Why would a developer use local storage for a web application?**
Developers use local storage for a web application to store data locally on a user's browser. This allows the application to persistently store information even after the user closes the browser, providing a seamless and personalized experience.

**What information should not be stored in local storage?**
Sensitive information, such as passwords and authentication tokens, should not be stored in local storage due to its accessibility by JavaScript and potential security risks. Critical data that requires server-side validation and control is better suited for other storage solutions.

**Local storage can store what type of data? How would you convert it to that type before storing?**
Local storage can store data as strings. To store other data types like objects or arrays, developers typically convert them to JSON strings using JSON.stringify() before storing. 

## Resources
[“The Past, Present, and Future of Local Storage for Web Applications”](https://diveinto.html5doctor.com/storage.html)
