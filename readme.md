# Resources

##Main
* [GT WebDev Site] (http://www.ccorgs.com/orgs/webdev/ "GT WebDev Site")
* [GT WebDev github] (http://www.ccorgs.com/orgs/webdev/ "GT WebDev github")

## Development Tools
### Git
Git is a popular distributed version control system. It integrates nicely with [Github] (www.github.com "Github") which is often used to facilitate collaboration on open source projects.

* [Try Git](http://try.github.io/levels/1/challenges/1/ "Try Git")
	
	Interactive tutorial that goes through the basics of git.

* [The Official Git Book](http://git-scm.com/book)

	Free online book. Contains the official discussion and explanation on how to use git as well as how it works (to some extent). Usually not needed since it's not quite a tutorial, but it's a fairly good read if you're interested in learning how git works and have a couple of hours to spare.

### [Chrome DevTools](https://developers.google.com/chrome-developer-tools/ "Chrome DevTools")
Chrome DevTools is built into Chrome. Some of its basic functions allow you to inspect elements on a webpage and run and debug JavaScript. An alternative for Firefox is [Firebug] (https://addons.mozilla.org/en-US/firefox/addon/firebug/ "Firebug")

* [Discover DevTools](http://discover-devtools.codeschool.com/ "Discover DevTools")
	
	Interactive tutorial that is fairly comprehensive. Starts from basics, but also goes into how to improve the performance of your site.

* Google I/O Dev-Tools keynotes - 1-hour long keynotes about features of Chrome Dev-Tools, occasionally mind-blowing.
  * [Google I/O 2010 - Google Chrome's developer tools](http://www.youtube.com/watch?v=TH7sJbyXHuk)
  * [Google I/O 2012 - Chrome Developer Tools Evolution](http://www.youtube.com/watch?v=3pxf3Ju2row)
  * [Google I/O 2013 - Chrome DevTools Revolutions 2013](http://www.youtube.com/watch?v=x6qe_kVaBpg)

### [Vim] (http://www.vim.org/)
A power text editor good for developing. High learning curve but very rewarding.

* [Derek Wyatt's Vim Tutorials](http://derekwyatt.org/vim/tutorials/novice/)

	A good comprehensive collection of screencasts and text explanation about how to get started with vim and how to use it fairly effectively. (note: this is the tutorial I originally used 3 years ago when I started using vim. -Dekel)

* [Vimcasts.com](http://vimcasts.org/)

	This is a good place to learn how to make the most of vim and learn how to operate it in general.

## HTML5/CSS3

* [Dive Into HTML5](http://diveintohtml5.info/index.html)

	Free book that goes into what's new with HTML5. You should probably already know some HTML. The book is really well done. It's beautiful, and it discusses browser compatibility, which is a big issue with web development.

## JavaScript
### Books
* [JavaScript: The Good Parts](http://www.amazon.com/JavaScript-Good-Parts-Douglas-Crockford/dp/0596517742/ref=sr_1_1?ie=UTF8&qid=1389631402&sr=8-1&keywords=javascript+the+good+parts/ "JavaScript: The Good Parts")
	
	Not an introduction book, but concisely highlights parts of JavaScript that should be used. Great reference for all JavaScript programmers.

* [Eloquent JavaScript](http://eloquentjavascript.net/ "Eloquent JavaScript")
	
	Free online book that goes from basics to through common programming paradigms used in JavaScript (Object-Oriented, Functional, etc.). Also covers recursion.

* [Effective JavaScrict](http://effectivejs.com/ "Effective JavaScript")

	(Advanced Topics) A collection of very specific features and examples that explain the nuances of JavaScript and some tips on how to use it more effectively; requires a good understanding of the language.
	
* [Secrets of the JavaScript Ninja](http://jsninja.com/)

	Supposedly a good resource for advanced JS techniques. (Disclaimer: I never read this book. -Dekel)

### Reference

* [JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/ "JavaScript Garden")

	A handy (and short) overview of some common javascript behaviors and features.

* [MDN: Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/JavaScript "MDN")

	The most comprehensive and trusted source of javascript documentation. Contains details for multiple platforms
	
* [wtfjs](http://wtfjs.com/)

	Collection of oddities of JavaScript. Things to watch out for.

### Tools

* [JSLint](http://www.jslint.com/)
	
	Douglas Crockford's (see "JavaScript: The Good parts" above) tool for code-quality checking for JavaScript. 

* [JSMin](http://fmarcia.info/jsmin/test.html)

	A browser-based tool for minifying javascript. Gets rid of unnecessary whitespace, replaces long variable names with single-letters, etc.
	
### Videos/Lectures/Keynotes

* Douglas Crockford's series on the history of JavaScript - very long and very comprehensive discussion of how javascript came about and the reasons for many of its oddities
  * [Volume 1](http://www.youtube.com/watch?v=JxAXlJEmNMg)
  * [Chapter 2](http://www.youtube.com/watch?v=RO1Wnu-xKoY)
  * [Act III](http://www.youtube.com/watch?v=ya4UHuXNygM)
  * [Episode IV](http://www.youtube.com/watch?v=Fv9qT9joc0M)
  * [Part 5](http://www.youtube.com/watch?v=47Ceot8yqeI)
  * [Scene 6](http://www.youtube.com/watch?v=QgwSUtYSUqA)
  * [Level 7](http://www.youtube.com/watch?v=UTEqr0IlFKY)
  * [Section 8](http://www.youtube.com/watch?v=taaEzHI9xyY)
  * [The JavaScript Programming Language](http://www.youtube.com/watch?v=v2ifWcnQs6M)
  * [An Inocnvinient API - The Theory of the DOM](http://www.youtube.com/watch?v=Y2Y0U-2qJMs)
  * [Advanced JavaScript](http://www.youtube.com/watch?v=DwYPG6vreJg)
  * [vaguely related - Crockford explains what monads are (recommended for haskell fanboys)](http://www.youtube.com/watch?v=dkZFtimgAcM)

### [Node.js] (http://nodejs.org/)

Node is platform best-used for creating scalable, networking applications. It comes with a JavaScript runtime environment, several useful built-in modules, and a handy package manager ([npm](https://www.npmjs.org/)). One of the best explanations of how it works, and why you should use it can be found [here](http://www.toptal.com/nodejs/why-the-hell-would-i-use-node-js).

### [d3.js] (http://d3js.org/)

d3, which stands for data-driven documents, is a JavaScript framework for creating information visualizations. It allows you to bind elements on a web page (such as circles, rectangles, lines, and other shapes) to data elements. d3 allows you to define the chracteristics of the elements on the web page like color, x-y coordinates, and thickness based on the values of your data. It can take a decent amount of tweaking to create something at first, but it's definitely worth learning.

* [d3 Official Gallery] (https://github.com/mbostock/d3/wiki/Gallery)

	Whether you have a visualization in mind for your data, or you're still at a loss on how to visualize it, this is a great place to start. There's a "visual index" of all kinds of visualizations made using d3, and most of the examples have the code and the data included.
	
* [Interactive Data Visualization for the Web] (http://chimera.labs.oreilly.com/books/1230000000345)

	This free book (the link to read online is on the page) is great for beginners. Explains a lot of things that might be confusing at first such as scales, axes, and transitions. 
	
* [Thinking with Joins] (http://bost.ocks.org/mike/join/)

	This article on how d3 adds, updates, and removes elements on a web page based on your data is a must-read. It's written by Mike Bostock, one of the creators of d3. It's concise and incredibly clear.

* [d3's Wiki] (https://github.com/mbostock/d3/wiki)

	d3's official wiki. Under the Resources heading, it contains links to the introduction (scroll down the main page of d3js.org), the example gallery, tutorials and talks, and the API reference.

## Design
* [Adobe Kuler] (https://kuler.adobe.com/create/color-wheel/) 

	Lets you easily create colors/swatches to use on your website! You can also browse other people's swatch creations.

## Other
### Browser Compatibility 
This is a good way to check what html, css, etc. is usable by a browser.
* [caniuse.com] (http://caniuse.com/)
* [html5please.com] (http://html5please.com/)
