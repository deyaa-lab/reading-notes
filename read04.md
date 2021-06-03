CSS 
allows you to create great-looking web pages

As we have mentioned before, CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.

A document is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.

CSS syntax
CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page. For example "I want the main heading on my page to be shown as large red text."

Three Ways to Insert CSS
There are three ways of inserting a style sheet:

External CSS:

   With an external style sheet, you can change the look of an entire website by changing just one file!

   Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.


Internal CSS:

   An internal style sheet may be used if one single HTML page has a unique style.


Inline CSS:

   An inline style may be used to apply a unique style for a single element.

   To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.



   CSS Syntax:

1.Set the text color with a HEX value:
```
   body {color: #92a8d1;}
```
2. Set the text color with a HSL value:
```
   body {color: hsl(89, 43%, 51%);}
```
CSS Specifications
All web standards technologies (HTML, CSS, JavaScript, etc.) are defined in giant documents called specifications (or "specs"), which are published by standards organizations

CSS Modules
As there are so many things that you could style using CSS, the language is broken down into modules. You'll see reference to these modules as you explore MDN and many of the documentation pages are organized around a particular module.

Once CSS has been specified then it is only useful for us in developing web pages if one or more browsers have implemented it. This means that the code has been written to turn the instruction in our CSS file into something that can be output to the screen. We'll look at this process more in the lesson How CSS works. It is unusual for all browsers to implement a feature at the same time, and so there is usually a gap where you can use some part of CSS in some browsers and not in others. For this reason, being able to check implementation status is useful.


