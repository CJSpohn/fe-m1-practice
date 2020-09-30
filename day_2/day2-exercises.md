## Day 2 Exercises

### Lists and Links
There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?
* Ordered lists include numbers between elements
* Unordered lists use bullet points or asterisks
* Definition lists are meant to provide definitions of each element

What is the basic structure of an element used to link to another website?
* `<a href="URLhere">Link Text</a>`

What attribute should you include in a link to open a new tab when the link is clicked?
* `target="_blank"`

How do you link to a specific part of the same page?
* First, add an id tag to a specific header or section
* Create a link where you want and use `href="#id"` within the link element

### CSS
What is the purpose of CSS?
* To create stylistic changes, positioning changes, and generally alter the "html blocks" that make up a webpage

What does CSS stand for? What does cascading mean in this case?
* cascading style sheets. In this case, cascade means that they inlay over each other. So applying css rules to a section creates those rules for all child sections. You can then override elements you want to appear differently.

What is the basic structure of a CSS rule?
* selector {property : value;}
* ex: `h1, h2, h3 {font-family: Arial;}`

How do you link a CSS stylesheet to your HTML document?
* with `<link href="css/style.css" type="text/css" rel="stylesheet" />`

When is it useful to use external stylesheets as opposed to using internal CSS?
* When you have a website that is multiple pages
* All of your webpages can use the same stylesheets
* Helps the site load faster


Describe what a color hex code is.
* A hex color is a 6 digit combination of letters and numbers specifying the red, green, and blue values of a color


What are the three parts of an HSL color property?
* Hue, saturation, lightness

In the world of typeface, what are the three main categories of fonts? What are the differences between them?
* serif - extra detail on the ends of main strokes of letters
* sans-serif - straight end to letters, cleaner design, clearer to read for small text
* monospace - each letter is the same width (often used in coding)

When specifying font-size, what are the main three units used?
* pixels
* percentages
* ems
