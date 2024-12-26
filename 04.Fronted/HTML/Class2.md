# Contents
- [HTML Tags](#html-tags)
- [Types of Tag](#types-of-tag)
  - [Meaning Tag or Semantic tag](#meaning-tag-or-semantic-tag)
  - [Structure Tag](#structure-tag)
  - [Formatting Tag](#formatting-tag)
- [What is Attribute](#what-is-attribute)
- [HTML List](#html-list)
  - [Order List](#order-list)
  - [Un Order List](#un-order-list)
  - [Description List](#description-list)
- [What is Emmets](#what-is-emmets)
- [Homework](#homework)
  - [Difference between Article and Section](#difference-between-article-and-section)
  - [How many `<h1>` tags use in websites?](#how-many-`<h1>`-tags-use-in-websites)

## HTML Tags
- An HTML (HyperText Markup Language) tag is a predefined element used to structure and format content on a webpage. Tags are the building 
  blocks of HTML and define how the browser should display content.
-----

## Types of Tag
- There are 3 types of tag.
------ 
## Meaning Tag or Semantic tag  
- Semantic HTML tags are tags that clearly describe their meaning and role in the structure of a webpage, both to browsers and 
  developers.
 - Examples: `<h1>` = Heading Tag  ,
 -   `<p>` = Paragraph Tag 
 -   `<a>` = ancher tag (for link) 
 -   `<table>`= Table Tag 
 -   `<img>` = Image Tag 
 -   `<ul>` = Un Orered List tag
-----
## Structure Tag
- Structure tags in HTML are used to organize and define the layout of a webpage. These tags help in creating a logical and hierarchical 
  structure for content, making it easier for browsers, developers, and search engines to interpret the document
  -  Examples:  `<html>` = The root element that encloses all content on the page. 
  -  `<head>` = Contains metadata, links to stylesheets, scripts, and the title of the document. 
  -  `<body>` = Contains the visible content of the webpage. 
  -  `<nav>` =Defines a set of navigation links. 
  -  `<main>` = Represents the main content of the document. 
  -  `<section>` = Defines a thematic grouping of content, typically with a heading. 
  -  `<article>` = Represents a self-contained piece of content, such as a blog post or news article. 
  -  `<aside>` = Contains content tangentially related to the main content, like a sidebar or advertisements. 
  -  `<footer>` = Represents the footer of a document or section. Commonly contains copyright or contact information.
  -----
## Formatting Tag
- A formatting tag is an element in markup languages like HTML, used to style and format text or content within a web document.
    -  Examples: `<b>` : Makes text bold 
    -  `<strong>` : Indicates strong importance (usually displayed as bold).
    -  `<i>`   : Makes text italic.
    -  `<em>`  : Indicates emphasized text (usually displayed as italic).
    -  `<code>`: Formats text as computer code.
    -  `<mark>`: Highlights text (yellow by default).
    -  `<u>`   : Underlines text.
    -  `<sub>` : Displays subscript text (smaller and below the baseline).
    -  `<sup>` : Displays superscript text (smaller and above the baseline).
    -----
## What is Attribute
-  An attribute provides additional information about an element. Attributes are always defined within the opening tag of an element.
    - Attributes consist of a name and a value, separated by an equals sign (=). The value is enclosed in quotes (" or '), though 
       quotes are optional in some cases.
     -  Examples:
  ![](/Image/Attributes in html.jpeg) 
## HTML List 
- Lists are used to group related items. There are three primary types of lists:
  ## Order List
  - An ordered list displays items in a specific order, usually numbered.
     ```html
    <ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
        </ol>
    ```
  ## Un Order List
  - An unordered list displays items without a specific order, typically marked with bullets.
   ```html
    <ul>
  <li>Apples</li>
  <li>Oranges</li>
  <li>Bananas</li>
    </ul>
  ```
  ## Description List
  - A Description List in HTML is used to define a list of terms and their corresponding descriptions. It is typically used for 
    glossaries, definitions, or other types of paired information.
   ```html
  <dl>
  <dt>HTML</dt>
  <dd>Hypertext Markup Language is the standard markup language for creating web pages.</dd>

  <dt>CSS</dt>
  <dd>Cascading Style Sheets is a style sheet language used for describing the look and formatting of a document.</dd>

  <dt>JavaScript</dt>
  <dd>A lightweight programming language used to create interactive effects within web browsers.</dd>
  </dl>
  ```
-----
## What is Emmets
-  Write a short abbreviation, and Emmet expands it into a full code block.
-  Example: `ul>li.item$*3`
-  [Emmet Documentation](https://docs.emmet.io/)
-----

## Homework
1. -Difference between Article and Section?
2. -How many `<h1>` tags use in websites?
     
## Difference between Article and section
- **Article**: What it is: A single, complete story or post.
                When to use it: For something that can make sense on its own, like: A blog post, A news article, A recipe
  - An article is like a full story inside that chapter.
  - Example:
  ```html
  <article>
  <h2>How to Recycle</h2>
  <p>Recycling is important to save the environment...</p>
   </article>
   ```
- **Section**: What it is: A part of the page to group related stuff together.
               When to use it: For breaking the page into parts, like: A chapter, A section with tips or steps
   - A section is like a chapter in a book.
   - Example:
  ```html
  <section>
  <h1>My Blog</h1>
  <article>
    <h2>Post 1</h2>
    <p>This is the first blog post.</p>
  </article>
  <article>
    <h2>Post 2</h2>
    <p>This is the second blog post.</p>
  </article>
  </section>
   ```
## How many `<h1>` tags use in websites?
   - you should use only one `<h1>` tag per page. This is because:
     Why Only One `<h1>`?
      1. SEO (Search Engine Optimization): Search engines, like Google, expect one main topic per page. The `<h1>` tells them what the 
         page is about.
      2. Accessibility: Screen readers for visually impaired users use the `<h1>` as the main heading of the page. Having more than one 
          can confuse users.
      3. Structure: The `<h1>` is the most important heading and represents the title or main idea of the page. Other headings (`<h2>`, 
        `<h3>`, etc.) are for subtopics.
  
