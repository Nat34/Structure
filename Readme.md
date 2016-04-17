# Structure-HTML
Client-side topic: HTML

This repository contains practice files.  These files were created to develop and learn HyperText Markup Language (HTML) syntax used to support user interface.

## Project: 
Structure a user interface with HTML.

## Drivers: 
To learn and use HTML to create and visually represent a webpage.

## Technology:  
HyperText Markup Language, Sublime Text Editor, Terminal, Unix Command Line, Web browsers (FireFox, Chrome, Safari, IE.9), Git, GitHub  

## Resources: 
Mozilla Developer Network (MDN), W3C HTML Validation Service, Learning Web App Development text, Lorem Ipsum

The typical workflow will be to open the file in Sublime text editor, make minor changes and reload the web browswer to see changes.  hello.html and index.html will be the primary files used throughout this project.  All changes in sequence can be viewed in commits.

## Notes:

**Document Object Model (DOM) and Trees**

DOM:
- HTML tags define a hierarchical structure called the DOM
- DOM represents objects defined via HTML and then later interacted with via a scripting language, like JavaScript. Tags define - DOM elements

Tree Diagrams:
- mental models of file systems
- mental models of the DOM

Identifying Structure:
- HTML = structure of a document

Visualizing Structure with a Tree:
- Identify structural elements (header, logo, navigation links, footer, etc)
- Create a tree diagram: specifies the contents of the various elements

DOM elements that are lower in the tree: 
- Descendants with path connecting
- Parent elements: above child elements
- Child elements: immediate descendants of parents
- Children of the `<body>` element: `<header>`, `<main>`, and `<footer>.`

**Structuring the `<main>` content:**

* `<h2>` and `<h3>`: represent heading text
* `<p>`:  represents paragraph content
* `<ul>`: represents unordered lists
* `<li>`: represents list items
* `<img>`: represents an image file / is a VOID tag, does not require a closing tag. Also, has alt attribute which contains a textual description of the image. This is important for creating accessible websites.

**Structuring the `<footer>` content:**

`<div>` and `<span>`: generic tags that allow one to create elements that represent some structure that is defined by ourselves

1. create two `<div>` elements: each has a "class" attribute, an attribute that one uses to add meaning to the generic `<div>` and `<span>` tags
 


**Web browser master list:**
* Firefox 3.5+
* Firefox for Android 19+
* Chrome 4.0+
* Internet Explorer 5.5+ *
* Safari 3.1+
* Opera 9+
* iOS Safari 5.0+
* Android Browser 3.0+
* Opera Mobile 12.1+
* Chrome for Android 2

**HTML international standards, specifications and maintenance:**
* W3C: [World Wide Web Consortium](http://www.w3.org/)
* WHATWG: [Web Hypertext Application Technology Working Group](http://www.whatwg.org/)
* Markup Validation Service: [MVS](http://validator.w3.org/)
* AFB: [Accessible Websites and Design](http://www.afb.org/info/programs-and-services/technology-evaluation/creating-accessible-websites/123)
