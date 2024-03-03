# Audio, Video, Images

## [Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

**Explain how the ability to use video and audio on the web has evolved since the early 2000s.**
- Early 2000s: Limited browser support, reliance on Flash.
- Mid to Late 2000s: Introduction of HTML5, native `<video>` and `<audio>` elements.
- 2010s: Standardization, improved cross-browser compatibility.
- Present: Advanced features like WebRTC, modern codecs.

**Describe the use of the `src` and `controls` attributes in the `<video>` element.**
- src: Specifies the video file URL
- controls: Adds playback controls

**Why is it important to have fallback content inside the `<video>` element?**
It ensures browser compatibility, accessibility, and resilience to network issues

**Write a very short story where `<audio>` and `<video>` are characters.**
In the kingdom of the Web, `<audio>` and `<video>` from Mozilla's guide teamed up to create captivating experiences. With fallback content as a safety net, they enchanted diverse users across the digital realm.

## [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

**How does Grid layout differ from Flex?**
- Grid Layout: Ideal for two-dimensional layouts, Grid allows precise control over rows and columns simultaneously. 
  - It's suitable for overall page structure.
- Flexbox (Flex): Primarily for one-dimensional layouts, Flex is great for distributing items along a single axis, either horizontally or vertically. 
  - It's handy for components within a layout.

**Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**
- Grid Container: The parent element where you apply display: grid;, establishing the grid context for its direct children.
- Grid Item: The children of the grid container, each becoming a grid item. You can place and control these items within the defined grid.
- Grid Line: The dividing lines that make up the structure of the grid. Can be horizontal (row lines) or vertical (column lines), delineating the grid into rows and columns.

## [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
**Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**
Apart from visual appeal, responsive images enhance website performance by optimizing file sizes for different devices. This reduces page load times and improves user experience, especially on mobile devices with varying screen sizes and network conditions.

**Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.**
- srcset: Specifies a list of image files and their sizes, allowing the browser to choose the most appropriate image based on the user's device characteristics.
- sizes: Defines the sizes of the image, indicating the layout slots the image will fill at different viewport widths.

**How is `srcset` more helpful for responsive images than CSS or JavaScript?**
- Automatic Selection: srcset allows the browser to automatically select the most appropriate image, considering factors like screen size and resolution, without additional scripting or styling.
- Optimized Performance: Unlike CSS or JavaScript, srcset reduces the need to load large images on small screens, optimizing performance by delivering only the necessary image assets.

## Resources
[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
[Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)