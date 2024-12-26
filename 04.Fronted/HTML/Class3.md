# Contents 
- [Elements in HTML](#elements-in-html)
- [What is Element](#what-is-element)
- [Types of Elements in HTML](#types-of-elements-in-html)
  - [Inline Element](#inline-element)
  - [Block Element](#block-element)
- [Homework](#homework)
  
## Elements in HTML


-------
## What is Element

----
## Types of Elements in HTML

 ## Inline Element

## Block Element

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
    - *Italic Tag* `<I>`	
       - 1. The `<i>` tag is used to display text in italics for visual styling.
       - 2. It doesn't add any special meaning or importance to the text.
    - *Emphasize Tag* `<em>`
       - 1. The `<em>`tag is used to add emphasis to text, and it often renders the text in italics by default.
       - 2. However, its primary purpose is to convey meaning — it tells the browser (and screen readers) that the text should be 
           emphasized.
----
 6. 

