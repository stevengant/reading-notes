# Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
    [MDN - Video and audio on the web](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
    Early video used plugins like Flash and Silverlight, both of which pose security and accessibility issues.
    Now video and audio elements can be used in HTML files, along with the availability of JavaScript APIs.

2. Describe the use of the src and controls attributes in the <video> element.
    [MDN - The video element](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
    The src attribute is used in video and audio elements just like img elements.

3. Why is it important to have fallback content inside the <video> element?
    [MDN - The video element](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
    Fallback content is the paragraph inside the video tags. This content will be displayed if the browser doesn't support the video element.

4. Write a very short story where <audio> and <video> are characters.
    A long time ago, the citizens of Browser were forced to use plugins like Flash and Silverlight in order to view audio and video content at the risk of their safety. Finally, twin brothers, Audio and Video Elements, came to town that were willing to stand up for the browsers. Audio and Video have since been ever vigilant in protecting the citizens of Browser.  


# A Complete Guide To Grid

1. How does Grid layout differ from Flex?
    [CSS-tricks - Introduction to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
    Grid is a two-dimensional system, whereas Flex is one dimmensional.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
    [CSS-tricks - Important CSS Grid terminology](https://css-tricks.com/snippets/css/complete-guide-grid/)
    - Grid Container: The element on which display: grid is applied; outer div.
    - Grid Item: The children/direct descendants of the grid container; inner div.
    - Grid Line: The dividing lines that make up the structure of the grid.


# Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
    [MDN - Why responsive images?](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
    Responsive images make it so that details are not lost when viewing on smaller or larger screens.

2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.
    [MDN - Resolution switching](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
    - srcset defines a set of images that the browser can choose from based on screen size.
    - sizes defines a set of media conditions and indicates what img would be best to choose. 

3. How is srcset more helpful for responsive images than CSS or JavaScript?
    [MDN - Resolution switching](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
    srcset allows the browser to choose the best image to fit the current screen size.