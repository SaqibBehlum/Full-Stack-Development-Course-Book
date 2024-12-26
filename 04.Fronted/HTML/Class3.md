# Contents 
- [Elements in HTML](#elements-in-html)
- [What is Element](#what-is-element)
- [Types of Elements in HTML](#types-of-elements-in-html)
  - [Inline Element](#inline-element)
  - [Block Element](#block-element)
- [Homework](#homework)
  
## Elements in HTML
   - HTML elements are the building blocks of a webpage. They structure and display the content. By combining different elements, you can 
     create a complete, functional website.
-------
## What is Element
![](
----
## Types of Elements in HTML
 ![](
 ## Inline Element
  - An inline element stays in the same line as other elements.
  - example of code: ```<p>This is a <span style="color: red;">red word</span> inside a paragraph.</p>```
  - example of tag `<span>`, `<a>`, `<strong>`, `<img>`

## Block Element
  - A block element starts on a new line and takes up the full width of the page by default.
  - Example of tag: `<div>`, `<p>`, `<h1>`, `<ul>`, `<li>`
-----
## Homework
 1. **Target Attribute:** The target attribute in anchor (`<a>`) elements specifies where to open the linked document
------
 2. **Common values for the target attribute:**
    - *self*: Default. Opens in the same tab.
    - *blank*: Opens in a new tab or window.
    - *parent*: Opens in the parent frame,If there is no parent, acts the same as _self
    - *top*: Opens in the full body of the window, ignoring frames.
------
 3. **How can we use anchor tag for bookmark in website?**
    - *Bookmark* :This is when a link on a page takes you to a specific section of that page or another page. It helps you move around a 
      long page quickly.
    - *Why Use This?*: To jump to a section in an article or FAQ.
    - *Tag for bookmark*: 
       - 1. Add an ID to the Target Element
       - 2. Assign a unique id to the element you want to link to. .
       - 3. Create an Anchor Link
    - Use the <a> tag with an href that matches the id of the target element.
    ```html
    <a href="#section2">Go to Section 2</a>
         <section id="section2">
		 <h2>Section 2</h2>
	   	 <p>This is the second part of the page.</p>
         </section>
       ```
 4. **Different between bold and Strong Tag?**
    - *Bold Tag* `<b>`
       - 1. Makes text bold for visual styling only.
       - 2. Does not add any special meaning.
    - *Strong Tag* `<Strong>` 
       - 1. Makes text bold and shows it is important.
       - 2. Adds semantic meaning (important for screen readers and SEO).
    -----
 5. **Different between Italic and Emphasize Tag?**			 
    - *Italic Tag* `<i>`	
       - 1. The `<i>` tag is used to display text in italics for visual styling.
       - 2. It doesn't add any special meaning or importance to the text.
    - *Emphasize Tag* `<em>`
       - 1. The `<em>`tag is used to add emphasis to text, and it often renders the text in italics by default.
       - 2. However, its primary purpose is to convey meaning — it tells the browser (and screen readers) that the text should be 
           emphasized.
----
 6. **What is Inline Block Element?**
     - Inline: Means the element stays in the same line as other elements, like words or links.
     - Block: Means the element can have width, height, padding, and margin (space inside and around it).
     - An inline-block element: acts like an inline element but also allows you to control its size like a block element.
-----
 7. **How to convert Inline Element into Block Element?**
     - To convert an inline element into a block element, you can use CSS to change its display property.
        ```css
        display: block;
        ```
    ----- 
 8. **How to convert Block Element into Inline Element?**
     - To convert a block element into an inline element, you can use the display property in CSS.
        ```css
       display: Inline;
       ```
    ----- 
 9. **<`img>` in Which type of Element?** 
     - The `<img>` tag is an inline element by default (it stays in the same line as text).
      ------- 
 10. **Nav bar in Single Line?**
       - You can use inline or inline-block elements for each navbar item to keep them on the same line.
       ```
       display: inline-block;
       ```



