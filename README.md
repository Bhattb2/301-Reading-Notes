# 301-Reading-Notes
Reading 01

## Table of Contents

Reading 01
## SMACSS and Responsive Web Design
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

* Supports JavaScript & PHP/PCRE RegEx.
* Results update in real-time as you type.
* Roll over a match or expression for details.
* Validate patterns with suites of Tests.
* Save & share expressions with others.
* Use Tools to explore your results.
* Full RegEx Reference with help & examples.
* Undo & Redo with ctrl-Z / Y in editors.
* Search for & rate Community Patterns.

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

Reading 05

# What is Heroku?

* Heroku is a cloud service provider and software development platform which facilitates fast and effective building, deploying and scaling of web applications.
* Heroku is a platform that enables developers to deploy, scale, and manage their applications without the need to set up and administer their own servers.
* Heroku offers a ready-to-use environment that allows you to deploy your code fast

# NODE

* js (Node) is an open source development platform for executing JavaScript code server-side.
* Node is useful for developing applications that require a persistent connection from the browser to the server and is often used for real-time applications such as chat, news feeds, and web push notifications.
* It is a popular tool for almost any kind of project!
* js is designed to build scalable network applications.
* js is similar in design to and influenced by, systems like Ruby's Event Machine and Python's Twisted. Node.js takes the event model a bit further

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
* want to build network-heavy applications
* want to build something quick that is supposed to be scalable
* want to build a real-time application
* are going to deal with JSON data a lot

You can use Node.js if you
* want to build computation-heavy applications
* are concerned about robustness and stability

Reading 07

# APIs Continued

## What Google Learned From Its Quest to Build the Perfect Team
My main take away is about working in teams/groups and how group dynamics play a role in the success or failure of the team. How well they work together and what attributes to their success. A great deal of research has gone into this and the article covered a lot of information - I was inspired. I was intrigued by the Google discovered that success didn’t come in a singular form - that groups of wildly different makeups could all work well together under different circumstances. With increased Psychological Safety and Social Sensitivity, so did Group Success. It’s heartening to read about these concepts being considered by a tech giant like Google. 
* the shared belief held by members of a team that the team is safe for interpersonal risk-taking
* a sense of confidence that the team will not embarrass, reject or punish someone for speaking up
* a climate characterized by interpersonal trust and mutual respect in which people are comfortable being themselves 
Success attributes:
* Sharing talk time
* High average social sensitivity
* Sensitive and sharing
* BEING NICE
* Creating a safe space for risk-taking
* Trust and respect
* Where folks can be comfortable
•	Psychological safety
Merging work life and life life
Creating more welcoming culture
Nobody wants to put on a work mask

## REST

### REST stands for REpresentational State Transfer.
* It means when a RESTful API is called, the server will transfer to the client a representation of the state of the requested resource. 
* In order for your APIs to be RESTful, minimum set constraint need to be followed when you write them. 
* The REST set of constraints will makes your APIs easier to use and also easier to discover for a developer

## Dark Sky API — Overview
The Dark Sky API allows you to look up the weather anywhere on the globe, returning (where available):
* Current weather conditions
* Minute-by-minute forecasts out to one hour
* Hour-by-hour and day-by-day forecasts out to seven days
* Hour-by-hour and day-by-day observations going back decades
* Severe weather alerts in the US, Canada, European Union member nations, and Israel

Reading 08

# SQL
## What is SQL?
* SQL (pronounced "ess-que-el") stands for Structured Query Language. 
* SQL is used to communicate with a database. 
* It is the standard language for relational database management systems.
* SQL statements are used to perform tasks such as update data on a database, or retrieve data from a database. 
* Some common relational database management systems that use SQL are: Oracle, Sybase, Microsoft SQL Server, Access, Ingres, etc. 
* Although most database systems use SQL, most of them also have their own additional proprietary extensions that are usually only used on their system. 
* The standard SQL commands such as "Select", "Insert", "Update", "Delete", "Create", and "Drop" can be used to accomplish almost everything that one needs to do with a database.

## Table Basics
* A relational database system contains one or more objects called tables. 
* The data or information for the database are stored in these tables. 
* Tables are uniquely identified by their names and are comprised of columns and rows. 
* Columns contain the column name, data type, and any other attributes for the column.
* Rows contain the records or data for the columns. 

Reading 09

# Functional Programming
## What is Functional Programming?

Functional Programming can be described as a programming archetype where one can mostly build and construct code using functions. These functions take input which is called as arguments then shows the output based on the inputs being taken which, given the same input always results in the same output.
It doesn’t allow any mutation nor shared state --- functions should remain pure and true to their expression under this paradigm. It is declarative rather than imperative/procedural.
Functional Programming can also be described simply a bunch of functions that don’t allow outside scope nor mutation of objects.
Instead we mutate arrays by adding/removing inside the scope to achieve a solution.
Functional is pure, straightforward and doesn’t mutate. It presents an answer to its elegant function in a straightforward manner.
Noteworthy is that JavaScript is a multi-paradigm programming language and Functional Programming is one of them. 
Functional Programming Features
Some of the most notable features of Functional Programming are:
First-Class Citizen Functions
What’s good about Functional Programming is its functions are first-class citizens: you can always insert functions inside a function without any restrictions present. 
Higher-Order Functions
A higher-order function is a function that gets a function as an argument. It may or may not return a function as its resulting output.

Benefits of Functional Programming
One of the reasons Functional Programming became popular were its benefits.
It doesn’t have side-effects and it’s immutable
One of the major benefits of using Functional Programming is its ability to not show any side-effects in the code.
 It reduces the likelihood that the code will introduce some bugs since it’s not going to mutate and the bug is easy to spot since it’s within the scope of the function. 
Once a variable has a value assigned to it, it is no longer subject to change.
Functional Programming is a Pure Function, this means that it won’t be borrowing any data outside of its scope, let alone allow any mutable objects.


# Refactoring
## What is Refactoring?
Code refactoring is the process of changing a program’s source code without modifying its external functional behavior, to improve some of the nonfunctional attributes of the software.
Basically, it is  re-writing code so that it will be easier to read, understand and easily adapt to changes in the future. .
Code Refactoring also helps us to cut down the size of the code resulting in performance gain(maybe?).

What to keep in mind during refactoring?
•	It should be done as a series of small iterations rather than re-writing the whole system again. 
•	Each iteration should be responsible for slightly improving the code while leaving the system in working order.
•	There should NOT be any new development during Code Refactoring – just the bare minimum.


Reading 10

# CALL STACK
## How do I use the call stack?

The call stack is where we find the stack frames that control program flow. When a function is called, it creates a stack frame that tells the computer how to return control to its caller after it has finished executing. Stack frames are also where local variables and function arguments are 'stored'. We can look at these stack frames to determine how our program is running. Finding the list of stack frames below the current frame is called a backtrace.


Call stack is a set of lines, which is usually read from top to bottom - meaning moving from current locations to callers. The bottom line was executed first. The top line is executed last and it is the current routine.
For example, if you have this call stack (short pseudo form):
* DoSomething
* DoWork
* Run

This means that Run procedure was executed first. Run called DoWork, which in turn called DoSomething


Reading 12

# EJS PARTIALS

EJS, embedded javascript, is a templating language. EJS combines data and a template to produce HTML. One of the most important features in EJS is its use of partials. Partials allow you to define something once, and then apply it to any page in your application.

Partial templates are larger sections of HTML which need to be included multiple times from multiple pages. Common uses for partial templates include headers, footers, site menus, login boxes, alerts, and so on.

* EJS Partials help us avoid repetition of the same code on several web pages.
For example, you may want the same header for several web pages.
* EJS partials work like EJS layouts too in creating a single fix content on a web page.

Note! You should have Node.js installed in your pc before you can start using EJS.
To begin, ensure you have EJS and express installed via npm. Unlike EJS Layouts, EJS partials can work without the express-ejs-layouts module. EJS partials apply in cases like creating objects like header, footer, div.
* For a web page to contain the partial, it must be connected to each partial via a line of code, unlike layouts which apply everywhere.


Reading 13

# What are web forms?
Web forms are one of the main points of interaction between a user and a web site or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage, or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

A web form's HTML is made up of one or more form controls (sometimes called widgets), plus some additional elements to help structure the overall form — they are often referred to as HTML forms. The controls can be single or multi-line text fields, dropdown boxes, buttons, checkboxes, or radio buttons, and are mostly created using the 'input element, although there are some other elements to learn about too.

Form controls can also be programmed to enforce specific formats or values to be entered (form validation), and paired with text labels that describe their purpose to both sighted and blind users.

Forms are one of the most powerful tools any website can feature, whether you're gathering email newsletter signups or work inquiries from potential clients. Webflow forms are fully customizable.

## Structure of your form 
To customize your form, you'll be editing the content inside the form wrapper → form element.

By default, the form includes some essential form fields and elements. You can add and remove any form element like an input field or a checkbox inside of the form block to customize your form as needed. You can also add other elements like images and text blocks.

## Form elements 
* **Label** — A label is used to describe the function or purpose of a form field.
* **Input** — The input field is used to collect single-line data, like a one-word response to a question.
* **File upload** — The file upload field allows site visitors to attach a file to their form submission. Read all about the File upload input and how you can customize it.
* **Text area** — The text area field allows visitors to input multi-line data, like a lengthy message.
* **Checkbox** — The checkbox field is best used for input data where the visitor can select one or multiple options. Learn more about checkboxes.
* **Radio button** — The radio button field is best used for input data where the visitor can select only one of many options. Learn more about radio buttons.
* **Select** — The select menu field behaves very similar to a dropdown element, where you can add a list of different options for your visitor to select from. You can also allow for multiple selections. Learn more about select inputs.
* **reCAPTCHA** — reCAPTCHA is a Google service that helps prevent spam through forms. Learn how to add reCAPTCHA in your forms.
* **Form button** — No form is complete without a submit button! This special button is what triggers the action of the form to complete.

## Input settings 
Each form element has different input settings based on its type.

* **Name** — All form elements have a name field. This is how you identify the field on form submissions.
* **Required** — Each form element has the required option. This lets you choose whether the user can submit the form without filling this field out.
* **Placeholder** — For input and text area fields, the placeholder is the text that displays in an empty input field. It can be a sample text or a description of the required information. You can style a placeholder text from the states menu.
* **Text** type — here, you choose what type of input you are asking for. For example, an input field with text type: email will only accept email addresses. A phone text type will only accept phone numbers. A password text type will hide the typed characters in the input field.
* **Autofocus** — If you want an input field to get focus when the page loads, check the autofocus option in the form settings. When a form element has autofocus checked, the page will load and scroll to that element if the form is below the fold.
