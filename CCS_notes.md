## Cascading Style Sheets: Intro

**CCS** stands for *cascading style sheets*; it's a stylesheet language which means it styles your document or is used to develop how it looks
    - *By using a stylesheet language like CSS, developers can separate the content from it's visual presentation

**CSS** is standard across web browsers, making it a core language of the web

## CSS Styling Basics 

The way your HTML information is presented relies entirely on a CSS stylesheet; if you don't create your own stylesheet what you see is defaults built into the web browser. 
Simply put, **CSS** allows you to control *exactly* how HTML elements look in the browser. 

So, if an **HTML** document contains content, your **CSS** document speficies how that content is rendered. 
     - For example, changing the color and size of text, or adding colums to the layout, or even special effects like animation. 

**CSS is a rule-based language**; you define the rules that are applied to different elements on your webpage. 

CSS code is broken up into parts, starting with the *selector* which picks what HTML elements are being styled. To style those elements, you use *declarations* which are broken up into *property* and *value* pairs. 

Consider something like this: 


h1 {

color: red;

font-size: 2.5em;

}


h1 is our *selector* and the *declarations* exist inside the { }. In the first line, the *property* is color, and the *value* is red. This example has two declarations.

It's important to note syntax here; closing the curly braces indicates that you are done defining the rules for the HTML element selected by, in this case, h1. 

Each **property** has allowable corresponding **values**
    - in the example above, we have color values that go with the color property, and size units that go with the font-size property. 


## How does CSS and HTML work together?
