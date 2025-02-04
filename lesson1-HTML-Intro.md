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
  
# First Website

- According to CHatGPT, the *index.html* serves an important role in web development.
  1. Default Homepage in a Directory
  2. Standard Naming convention; *most websites use index.html as the main entry point*
  3. Easier File Organization; *browsers automatically load where an index.html is present
  4. Overall good practice; index.html is a great way to structure content for static sites.

 -Here's a basic start to an index.html file: 

 ```
 <!doctype html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>My test page</title>
  </head>
  <body>
    <p><strong>Hello World!</strong></p>
  </body>

```

- `<!doctype html>` is a required preamble; it makes sure your document behaves correctly.
- `<html></html>` wraps all the content on the page; also known as the *root element*
  - this also includes the `lang` attribute, which sets the language of the document. In this case, to US English.
- `<head></head>` Contains all the stuff that you **aren't** showing to your viewers.
- `<meta name="viewport" content="width=device-width">` ensures that the page renders at the width of the viewport, in this case rendering at the width of the device (ie shrinks for mobile viewing)
- `<title></title>` This sets the title of your page (*pretty self explanatory, huh?*)
- `<body></body>` This contains **ALL** content that you want to show to web users visiting your page.
  - In this case, if you visited this page you'd see "Hello, World!" displayed in bold.

**This is just *some* of the syntax for HTML.** 


