# Basic JavaScript

* What is [JavaScript](https://en.wikipedia.org/wiki/JavaScript)?
* How to JavaScript
* Variables
* Logic Control
* Interacting with the DOM

### Scripts

JavaScript or JS is the programming language of web browsers. It lets you add behavior and interactivity to your website.

* Can be placed within `<head>` or `<body>`, but ideally before the closing `</body>` tag
* Case sensitive
* Semicolons at the end of lines are optional
* Ignores consecutive whitespaces

```
<script>...</script>

separate file.js
```
> *Two ways of adding scripts to HTML*

> *Recommended to have JS in their own files*


#### JavaScript Reference:
> https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference


### Outputting JS

Let's JavaScript! There's a JS console in your browser. Find it. Let's see how JS can communicate with us in several ways:

Alert box: `window.alert('Hello world!')`

HTML output: `document.write('Hello world!')`

HTML element: `element.innerHTML('Hello world!')`

Browser console: `console.log('Hello world!')`

Why? This gives you a quick way of letting you know what's happening in your code.


### Comments

There are two ways of commenting in JS:

Single-line: anything after `//`

Multiple lines: anything between `/*` and `*/`

Again, why? You wouldn't want to delete stuff right away and type them all over again all the time. Comments let us do that with little effort. Eventually when you're writing more complex code, comments would help the reader.


### Some Common Keywords

Keyword dump! Let's stick to these common keywords for now:

`var` or `let`: Declares a variable

`for ((initialization); (condition); (final-expression)) {}`: For as long as condition is true, a block of statements will be executed. Ihe initialization will be executed at the beginning of the loop. The final-expression is executed at the end of each iteration of the loop.

`if (expression) {} [ else [ if ] {} ]`: Depending on a condition, a block of statements may or may not be executed

`function () {}`: Declares a function

`return`: Exits a function

`try {} [ catch () ] {} [ finally {} ]`: Implements error handling to a block of statements

* Parentheses:  expressions
* Curly brackets: block of code
* *Square brackets: optional parts of the pattern*
