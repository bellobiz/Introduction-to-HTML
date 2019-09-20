INTRODUCTION TO HTML
Images
All of the elements you’ve learned about so far (headings, paragraphs, lists, and spans) share one thing in common: they’re composed entirely of text! What if you want to add content to your web page that isn’t composed of text, like images?

The <img> tag allows you to add an image to a web page. Most elements require both opening and closing tags, but the <img> tag is a self-closing tag. Note that the end of the <img> tag has a forward slash /. Self-closing tags may include or omit the final slash — both will render properly.

<img src="image-location.jpg" />
The <img> tag has a required attribute called src. The src attribute must be set to the image’s source, or the location of the image. In this case, the value of src must be the uniform resource locator (URL) of the image. A URL is the web address or local address where a file is stored.

Instructions
1.
Under the Media <h2> heading, add an image. Use the following URL as the source (src) for the image:

https://s3.amazonaws.com/codecademy-content/courses/web-101/web101-image_brownbear.jpg