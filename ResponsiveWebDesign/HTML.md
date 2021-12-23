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

- As a convention, all HTML tags are written in lowercase

2. Comment HTML
   - Commenting is a way that you can leave comments for other developers within your code without affecting the resulting output that is displayed to the end user.
   - Commenting is also a convenient way to make code inactive without having to delete it entirely.
   - Comments in HTML start with `<!-- and end with a -->`
3. HTML Elements
   - HTML5 introduces more descriptive HTML tags. These include `main`, `header`, `footer`, `nav`, `video`, `article`, `section` and others.
   - These tags give a descriptive structure to your HTML, make your HTML easier to read, and help with Search Engine Optimization (SEO) and accessibility. The `main` HTML5 tag helps search engines and other developers find the `main` content of your page.
4. Add images to your website
   - You can add images using the `img` element, and point to a specific image's URL using the `src` attribute.
     - Note that `img` elements are self-closing.
     - All `img` elements must have an `alt` attribute. The text inside an `alt` attribute is used for screen readers to improve accessibility and is displayed if the image fails to load.
       - Note: If the image is purely decorative, using an empty `alt` attribute is a best practice.
       - Ideally the `alt` attribute should not contain special characters unless needed.
   - Example
     `<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">`
5. Link to External Pages with Anchor Elements
   - You can use `a` (anchor) elements to link to content outside of your web page.
   - `a` elements need a destination web address called an `href` attribute. They also need anchor text. Here's an example:
     `<a href="https://www.freecodecamp.org">this links to freecodecamp.org</a>`
6. Link to Internal Sections of a Page with Anchor Elements
   - `a`(anchor) elements can also be used to create internal links to jump to different sections within a webpage.
   - To create an internal link, you assign a link's `href` attribute to a hash symbol # plus the value of the id attribute for the element that you want to internally link to, usually further down the page. You then need to add the same `id` attribute to the element you are linking to. An `id` is an attribute that uniquely describes an element.
   - Below is an example of an internal anchor link and its target element:
     `<a href="#contacts-header">Contacts</a>`
     ...
     `<h2 id="contacts-header">Contacts</h2>`
     When users click the Contacts link, they'll be taken to the section of the webpage with the Contacts heading element.
7. Nest an Anchor Element within a Paragraph

   - You can nest links within other text elements.
     -EXAMPLE:
     `<p>`
     Here's a `<a target="_blank" href="https://www.freecodecamp.org">` link to www.freecodecamp.org</a> for you to follow.
     `</p>`
     Let's break down the example. Normal text is wrapped in the `p` element:
     `<p>` Here's a ... for you to follow. `</p>`
     Next is the anchor element `<a>` (which requires a closing tag `</a>)`:
     `<a> ... </a>`
     target is an anchor tag attribute that specifies where to open the link. The value \_blank specifies to open the link in a new tab. The href is an anchor tag attribute that contains the URL address of the link:
     `<a href="https://www.freecodecamp.org" target="_blank"> ... </a>`
     The text, link to www.freecodecamp.org, within the a element is called anchor text, and will display the link to click:
     `<a href=" ... " target="...">`link to freecodecamp.org`</a>`
     The final output of the example will look like this:Here's a link to www.freecodecamp.org for you to follow.

8. Make Dead Links Using the Hash Symbol

- Sometimes you want to add a elements to your website before you know where they will link.
- For example: `href="#"`

9. Turn an Image into a Link

- You can make elements into links by nesting them within an a element.
- EXAMPLE:
  `<a href="#"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="Three kittens running towards the camera."></a>`

10. Create a Bulleted Unordered List

- HTML has a special element for creating unordered lists, or bullet point style lists.
- Unordered lists start with an opening `<ul>` element, followed by any number of `<li>` elements. Finally, unordered lists close with a `</ul>`.
- EXAMPLE:

  ```
  <ul>
    <li>milk</li>
    <li>cheese</li>
  </ul>
  ```

  11. Create an Ordered List

  - HTML has another special element for creating ordered lists, or numbered lists.
  - Ordered lists start with an opening `<ol>` element, followed by any number of `<li>` elements. Finally, ordered lists are closed with the `</ol>` tag.
  - EXAMPLE:

  ````
    <ol>
      <li>Garfield</li>
      <li>Sylvester</li>
    </ol>
    ```
  ````

  12. Create a Text Field

  - Input elements are a convenient way to get input from your user.
  - You can create a text input like this:
    ```
    <input type="text">
    ```
    Note that input elements are self-closing.

13. Add Placeholder Text to a Text Field

    - Placeholder text is what is displayed in your input element before your user has inputted anything.
    - You can create placeholder text like so:

    ```
    <input type="text" placeholder="this is placeholder text">
    ```

    Note: Remember that input elements are self-closing.

14. Create a Form Element
    - You can build web forms that actually submit data to a server using nothing more than pure HTML. You can do this by specifying an action attribute on your form element.
    - EXAMPLE:
    ```
    <form action="/url-where-you-want-to-submit-form-data">
      <input>
    </form>
    ```
15. Add a Submit Button to a Form
    - Let's add a submit button to your form. Clicking this button will send the data from your form to the URL you specified with your form's action attribute.
    - EXAMPLE:
    ```
    <button type="submit">this button submits the form</button>
    ```
