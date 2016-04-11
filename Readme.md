This folder contains practice files.  These files were created to develop and learn HyperText Markup Language (HTML) syntax used to support user interface.

Project: Structure a user interface with HTML.

Drivers: To learn and use HTML to create and visually represent a webpage.

Technology:  HyperText Markup Language, Sublime Text Editor, Terminal, Unix Command Line, Web browsers (FireFox, Chrome, Safari, IE.9), Git, GitHub  

Resources: Mozilla Developer Network (MDN), W3C HTML Validation Service, Learning Web App Development text, Lorem Ipsum

The typical workflow will be to open the file in Sublime text editor, make minor changes and reload the web browswer to see changes.  hello.html and index.html will be the primary files used throughout this project.  All changes in sequence can be viewed in commits.

Notes:

Document Object Model (DOM) and Trees: 

DOM:
HTML tags define a hierarchical structure called the DOM
DOM represents objects defined via HTML and then later interacted with via a scripting language, like JavaScript. Tags define DOM elements

Tree Diagrams:
mental models of file systems
mental models of the DOM

Identifying Structure:
HTML = structure of a document

Visualizing Structure with a Tree:
1.Identify structural elements (header, logo, navigation links, footer, etc)
2.Create a tree diagram: specifies the contents of the various elements

			<body>

  <header> 		<main>		<footer>
<h1> <nav>            <div> <img>      <div> <div>
		      <h2>	       <h5>  <h5> <ul>
  		      <p>              <p>      <li>  <li>
		      <h3>	       <p>      <li>  <li>
		      <p>              <p>      <li>  <li>


DOM elements that are lower in the tree: descendants with path connecting

Parent elements: above child elements
Child elements: immediate descendants of parents
Children of the <body> element: <header>, <main>, and <footer>.

Structuring the <main> content:

<h2> and <h3>: represent heading text
<p>:  represents paragraph content
<ul>: represents unordered lists
<li>: represents list items
<img>: represents an image file / is a VOID tag, does not require a closing tag. Also, has alt attribute which contains a textual description of the image. this is important to make the page accessible by the visually impaired, who often use screen readers when browsing the Internet.

Structuring the <footer> content:

<div> and <span>: generic tags that allow one to create elements that represent some structure that is defined by ourselves

1.create two <div> elements: each has a "class" attribute, an attribute that one uses to add meaning to the generic <div> and <span> tags
 


Web browser master list:
Firefox 3.5+
Firefox for Android 19+
Chrome 4.0+
Internet Explorer 5.5+ *
Safari 3.1+
Opera 9+
iOS Safari 5.0+
Android Browser 3.0+
Opera Mobile 12.1+
Chrome for Android 2

HTML international standards and specifications maintaince:
W3C: World Wide Web Consortium http://www.w3.org/
WHATWG: Web Hypertext Application Technology Working Group http://www.whatwg.org/
Markup Validation Service: http://validator.w3.org/
