[Info comes from](https://developer.mozilla.org/en-US/docs/Web/HTML)

# HTML Introduction
**HTML stands for HyperText Markup Language**

- HTML is used to define the meaning and structure of web content, while *CSS* describes the webpage's appearance and *JavaScript* defines function
- "Hypertext" refers to links that connect webpages together- **Links** are fundamental to creating Web content, making you an active particpant

  ## HTML Vocab
  **Markup** is how HTML annotates text, images, etc. for display in a web browser
  **Elements** exist in tags surrounded by "<" and ">". The name of the element inside the tag is case case-insensitive, meaning <Tag> and <tag> are the same.
    - The recommended practice for elements is to use **all lowercase**.

  # Creating Content w/ HTML

  - HTML consists of a series of *elements* that you use to make content appear/act a certain way.
  - Enclosing *tags* can make a word do things, such as hyperlink somewhere else, appear bold or italicized, make the font bigger/smaller, etc.
 
- ## Examples

- - *Elements* exist within certain syntax. For example, creating a paragraph would look like this:

    <p>My cat is very grumpy</p>

- If we break down how this works:
  
 ![Alt Text](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Creating_the_content/grumpy-cat-small.png)

- Showing the syntax used to denote the paragraph, which are the *tags*, with the entire structure being the *element*

  ### Attributes

- Within *tags* we can also add *Attributes*; which contain information about the *element* that shouldn't appear in the content.

![Alt Text](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Creating_the_content/grumpy-cat-attribute-small.png)

- Breaking down this example, **class** is the *name* of the attribute, while **editor-note** is the *value* of the attribute.

- *Attributes* that set a value always have:
  1. A space between it and the element name
  2. The attribute name followed by an equal sign
  3. The attribute value wrapped by " "
 
### Nesting Elements

- *Nesting* is putting elements inside other elements; this changes the style to put emphasis on certain parts of the element.

<p>My cat is <strong>very</strong> grumpy.</p>

- In this case, the **Bold** word is identified using the "strong" tag.
  - (remember tags are enclosed by "<" and ">")

- To *nest* elements, they have to be clearly closed withing "<" ">" annotating them as seperate tags, inside or outside one another, in order for the styling to function properly.


### Void Elements

- Not all *elements* enclose *content*. Tese are called **void elements**.

- A perfect example of this is the "img" tag, which does not use a closing tag to denote the element. This is because an image doesn't wrap conent to affect it, but rather embeds an image to the page.
  
