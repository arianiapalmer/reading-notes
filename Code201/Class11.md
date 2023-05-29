# Foundations of Software Development: Class 11

* Class notes for Code 201 with code fellows

## Class 11

### *Reading 11: Assorted Topics*

#### [Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

The ability to use web and audio has evolved from having to use plugins like flash or silverlight, to it being accessible natively to HTML5.
In the video element, the src attribute provides a path to the video you want to use, and the controls attribute allows for the user to control video and audio playback.
It is important to fallback content in the video element not all browsers support all media types and this lets a user know that there is content but it cant be viewed and why it cant be viewed

#### [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

Whereas flex layout allows you to keep content in place with different screen sizes based on a flow direction, grid allows you to do the same based on specific sections determined by gridlines. Flex is best suited for smaller scale websites while grid is best suited for larger scale websites.
Grid container is a parent that defines the element as the container for the grid for which child properties are to follow; grid item is a direct descendant, or child, of grid; and grid line is the dividing lines that make up the structure of a grid.

#### [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

Developers should make images responsive not only to make it look more appealing across different screen sizes, but to also not waste the bandwidth of users who are viewing a site on a mobile screen. The srcset attribute defines the set of images the browser is allowed to choose between and what size each image is. The sizes attribute defines a set of media conditions and indicates what image size would be best to choose when certain media conditions are true. The srcset attribute is most helpful for responsive images than css or js because it effects screen loading times.
