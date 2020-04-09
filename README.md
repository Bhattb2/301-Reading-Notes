# 301-Reading-Notes
Reading 01

## Table of Contents

## Day 1 Notes
    1. Responsive design allows the content of the page to adjust to the screen size in the desktop or the mobile device. 
    2. Relative Viewport Lengths are relative lengths associated specifically to the viewport size of the browser or the device.
        a. vw = Viewport's width
        b. vmin= Minimum of the Viewport's height and width
        c. vh = Viewport's height
        d. vmax = Maximum of the viewport's height and width
    3. Responsive allows to have views set in a couple of ways: em, percentages. In either case the content adjusts according to the units prescribed.
    4. Media queries are media extension that allow to specify  various styles for individual browsers and device situations.

Reading 02

## jQuery, Events, and The DOM
    1.jQuery makes it straightforward to set up event-driven responses on page elements. These events are often triggered by the end user's interaction with the page, such as when text is entered into a form element or the mouse pointer is moved. In some cases, such as the page load and unload events, the browser itself will trigger the event.
    2. jQuery offers convenience methods for most native browser events. 
    3. These methods — including .click(), .focus(), .blur(), .change(), etc. — are shorthand for jQuery's .on() method. The on method is useful for binding the same handler function to multiple events, when you want to provide data to the event handler, when you are working with custom events, or when you want to pass an object of multiple events and handlers.
    4. jQuery is a powerful and widely used JavaScript library to simplify common web scripting task.
    5. jQuery is a fast, lightweight, and feature-rich JavaScript library that is based on the principle "write less, do more". It's easy-to-use APIs makes the things like HTML document traversal and manipulation, event handling, adding animation effects to a web page much simpler

Reading 03

## Fexbox and Templating
    1. JavaScript templates are a method of separating HTML structure from the content contained within. 
    2. Templating systems generally introduce some new syntax.
    3. Some of the popular templating engines out are: Mustache, Handlebars and jQuery Template.
    4. Mustache is a multi-language, logic-less templating system. The mustache.js implementation is just one of many.  
    5. Handlebars.js is built on top of Mustache and is mostly compatible with Mustache templates. It provides everything mustache.js provides, plus it supports block expressions and precompiled templates.

Reading 04

##  Responsive Web Design and Regular Expressions

### What Regular Expressions Are Exactly – Terminology 
Basically, a regular expression is a pattern describing a certain amount of text. Regular Expressions (also called Regex or Regexp) is a pattern in which the rules for matching text are written in form of metacharacters, quantifiers or plain text. They are strings in which “what to match” is defined or written. 
Regex is used for finding patterns or replacing the matched patterns
RegExr is an online tool to learn, build, & test Regular Expressions (RegEx / RegExp).

    •	Supports JavaScript & PHP/PCRE RegEx.
    •	Results update in real-time as you type.
    •   Roll over a match or expression for details.
    •	Validate patterns with suites of Tests.
    •	Save & share expressions with others.
    •	Use Tools to explore your results.
    •	Full RegEx Reference with help & examples.
    •	Undo & Redo with ctrl-Z / Y in editors.
    •	Search for & rate Community Patterns.

CSS Grid Layout introduces a two-dimensional grid system to CSS. Grids can be used to lay out major page areas or small user interface elements. This article introduces the CSS Grid Layout and the new terminology that is part of the CSS Grid Layout Level 1 specification. The features shown in this overview will then be explained in greater detail in the rest of this guide.

### What is a grid?
A grid is an intersecting set of horizontal and vertical lines – one set defining columns, and the other, rows. Elements can be placed onto the grid, within these column and row lines. CSS grid layout has the following features:

#### Fixed and flexible track sizes
You can create a grid with fixed track sizes – using pixels for example. This sets the grid to the specified pixel which fits to the layout you desire. You can also create a grid using flexible sizes with percentages or with the new fr unit designed for this purpose.

#### Item placement
You can place items into a precise location on the grid using line numbers, names or by targeting an area of the grid. Grid also contains an algorithm to control the placement of items not given an explicit position on the grid.

#### Creation of additional tracks to hold content
You can define an explicit grid with grid layout. The Grid Layout specification is flexible enough to add additional rows and columns when needed. Features such as adding “as many columns that will fit into a container” are included.

#### Alignment control
Grid contains alignment features so we can control how the items align once placed into a grid area, and how the entire grid is aligned. 

#### Control of overlapping content
More than one item can be placed into a grid cell or area and, they can partially overlap each other. This layering may then be controlled with the z-index property.
Grid is a powerful specification that, when combined with other parts of CSS such as flexbox, can help you create layouts that were previously impossible to build in CSS. It all starts by creating a grid in your grid container.

Reading 06

# Node.js
## What Node.js really is.
Node.js is a software platform to create fast, scalable web applications quickly. These applications also use JavaScript on the server and web browsers. JavaScript is limited to the browser. So, some people took the engine that powered JavaScript in Google Chrome and put it out on the table.
Node.js makes it easy to build plugins, frameworks, and other code used in different applications. You can make JavaScript work outside of your browser. You can plug in various packages, modules, and middleware and use it to build web-apps, desktop-apps, and mobile-apps.
Since the outside environment is much larger and so very different from that of a browser, we consider JavaScript-on-the-table as a separate entity in itself and call it Node.js.
### Feature 1: It is asynchronous.
Much like JavaScript, Node.js is asynchronous (or non-blocking). 
What it means to be asynchronous is that, code on line 10 may start executing before code on line 1 completes. It doesn’t always go line-by-line in a synchronous manner.
JavaScript is a programming language, Node.js is not. A Node.js program is still a JavaScript program. It is just not written to run on web-browsers. 
### Feature 2: It is single-threaded.
Unlike in a server, where a thread is spawned on a per-request basis, a single thread is responsible for handling all the client requests in Node.js. 
### Feature 3: It is event-driven.
Node.js is event-driven and its event-loop makes it a great choice for real-time applications. 
#### When to use Node.js
You can use Node.js if you:
•	want to build network-heavy applications
•	want to build something quick that is supposed to be scalable
•	want to build a real-time application
•	are going to deal with JSON data a lot

You can use Node.js if you
•	want to build computation-heavy applications
•	are concerned about robustness and stability
