# Basic HTML and HTML5

1. HTML and HTML5 are essentially the same thing, HTML5 is just an updated version. You can use the terms interchangeably.
   - Heading
     - Opening tags look like this: `<h1>`
     - Closing tags look like this: `</h1>`
     - `h1` elements are often used for main headings, while `h2` elements are generally used for subheadings. There are also `h3`, `h4`, `h5` and `h6` elements to indicate different levels of subheadings.
   - Paragraphs
     - p elements are the preferred element for paragraph text on websites. p is short for "paragraph".
       You can create a paragraph element like this:
       `<p>I'm a p tag!</p>`
2. As a convention, all HTML tags are written in lowercase
3. Comment HTML
   - Commenting is a way that you can leave comments for other developers within your code without affecting the resulting output that is displayed to the end user.
   - Commenting is also a convenient way to make code inactive without having to delete it entirely.
   - Comments in HTML start with `<!-- and end with a -->`
4. HTML Elements
   - HTML5 introduces more descriptive HTML tags. These include `main`, `header`, `footer`, `nav`, `video`, `article`, `section` and others.
   - These tags give a descriptive structure to your HTML, make your HTML easier to read, and help with Search Engine Optimization (SEO) and accessibility. The `main` HTML5 tag helps search engines and other developers find the `main` content of your page.
5. Add images to your website
   - You can add images using the `img` element, and point to a specific image's URL using the `src` attribute.
     - Note that `img` elements are self-closing.
     - All `img` elements must have an `alt` attribute. The text inside an `alt` attribute is used for screen readers to improve accessibility and is displayed if the image fails to load.
       - Note: If the image is purely decorative, using an empty `alt` attribute is a best practice.
       - Ideally the `alt` attribute should not contain special characters unless needed.
   - Example
     `<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">`
6. Link to External Pages with Anchor Elements
   - You can use `a` (anchor) elements to link to content outside of your web page.
   - `a` elements need a destination web address called an `href` attribute. They also need anchor text. Here's an example:
     `<a href="https://www.freecodecamp.org">this links to freecodecamp.org</a>`

# CSS
