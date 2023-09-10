+++
title = 'Getting started with JavaScript for Beginners'
author = 'Akorede Da silva'
date = 2023-09-10T07:40:56+01:00
draft = false
+++

![Getting started with JavaScript](/assets/learning%20JavaScript.jpg)

## TABLE OF CONTENT
- [Link to Introduction](#introduction-to-javascript-for-beginners)
    - [Why learn JavaScript](#why-learn-javascript)
    - [How is JavaScript used in web development](#how-is-javascript-used-in-web-development)
- [Javascript fundamentals](#javascript-fundamentals)
    - [Variables](#variables)
    - [Data types](#data-types)
    - [Functions](#functions)
    - [JavaScript file naming conventions](#javascript-file-naming-convention)
- [Javascript DOM](#javascript-dom)
    - [Selecting the HTML elements in the DOM](#selecting-the-html-element-in-the-dom)
    - [Manipulating HTML elements in the DOM](#manipulating-html-elements-in-the-dom)
- [JavaScript Libraries](#javascript-libraries)
    - [Popular JavaScript libraries](#popular-javascript-libraries)
    - [What are JavaScript frameworks](#what-are-javascript-frameworks)
    - [Popular JavaScript frameworks](#popular-javascript-frameworks)
- [Conclusions](#conclusion)
    - [Resources for learning JavaScript](#resources-for-learning-javascript)



### INTRODUCTION TO JAVASCRIPT FOR BEGINNERS 
JavaScript is a lightweight, cross-platform, and dynamic computer programming language well known for the development of web pages. JS as JavaScript is fondly called can be used for client-side (Front-end) development as well as Server-side (Back-end) development. JavaScript was first known as LiveScript, but Netscape changed its name to what it is today due to Java’s popularity. It allows client-side script to interact with the user and make dynamic pages.

### WHY LEARN JAVASCRIPT
JavaScript is essential in today’s digital landscape as it powers the interactive and dynamic elements of websites and cross-platform mobile applications, making it a fundamental skill for developers. Below are reasons why you should take up JavaScript.
- JavaScript is ideal for Newbies: It is one of the most accessible languages if you want to venture into website development, as it has a large and active community willing to help with JavaScript resources, tutorials, and support.
- Browser compatibility: It runs in all modern browsers as it is the default language of the internet. Its use is a necessary part of any user experience in the browser.
- Frameworks and Libraries: It has a diverse range of frameworks with each having its own merit over the other. A few examples of JavaScript are React, Vue, Angular, DanfoJs, Ember, Node, and Svelte.
- Cross-Platform development: JavaScript uses transcend beyond the internet. It powers smart home devices by working with the Internet of Things (IoT), Creating cross-platform applications with frameworks like React Native as well as creating native applications for IOS and Android.
- High demand: With an increasing number of businesses going digital. There is a constant demand for developers who are familiar with variants of JavaScript frameworks, and you get to earn competitive salaries due to their grasp of the language.
- Interactive element: JavaScript is at the core of building a visually appealing web page that provides an intuitive user experience. Attracting the attention of users to web pages of business owners is important and one of the ways developers can do this is through animations and interactive features.

### HOW IS JAVASCRIPT USED IN WEB DEVELOPMENT
JavaScript has a wide use case in the digital world today. It enables interactions and dynamic content on the website.
- Developing the server side of the browser using NodeJS, which is a runtime environment that allows JavaScript to run outside the browser
- Validating user input and providing feedback on forms, such as checking if a user is 18+ if they have provided a valid email address, or if the password strength Is good enough for the user to proceed.
- It can also be used in developing progressive web applications for Windows, Mac OS, and Linux.
- JavaScript is also used to develop games using frameworks such as Babylon.JS to create 2D and 3D games that run in the browser.
- Developing platforms that use machine learning and artificial intelligence uses JavaScript libraries such as TensoFlow.JS to create and train neural networks.
- It can also be used to create single-page applications (SPAs), which are websites that load a single HTML page.

## JAVASCRIPT FUNDAMENTALS
JavaScript coding is called scripting and it doesn’t require any setup. Now let’s understand some basic JavaScript terms.

### VARIABLES
JavaScript variables are containers that hold value. It can be used to store different data types including string, number, Boolean, array, and objects. The benefits of variables in JavaScript are numerous as they make your code readable and organized, and it also help you control the flow of your code. It is best to learn how to declare and use variables if you are new to JavaScript.
- Constant variables are declared using const a keyword, and the value passed to the variable cannot be changed once assigned to it.
```
const name = `Corey Dasilva`;
console.log(name);
```
- Array variables store a collection of data elements.
```
Var array = [74,89,78,91];
```

### DATA TYPES
JavaScript has 7 distinct data types which are explained below.
- String variable: It stores strings of text. 
```
var string = “Getting started with JavaScript”;
```
- Number variable: It stores different number types which include floats, and integers. 
```
var number = 2023; , var float = 22/7;
```
- Symbol variable: It stores unique symbol values. To call the symbol function in JavaScript, use 
```
var symbol = symbol( );
```
- Undefined variable: it is used to indicate an unassigned variable. 
```
var value;
```
- Boolean variable: This variable is used to store True or False values. Pay attention to how the variable is written. 
```
var isTrue = true; var isFalse = false;
```
- BigInt Variable: This helps you store integer values that become too big to be represented by a single number.
```
var bigInt = 1234567890x;
```
- Null variable: This is used to declare a value that is not defined. 
```
var value = null;
```

### FUNCTIONS
A JavaScript function is a task-performing block of code that takes an input and returns output. JavaScript function is defined with a keyword, followed by a name, followed by a parentheses (). They can be used to calculate a value, display output, validate input, create reusable code, manipulate data, and control the flow of execution. 
Below is a JavaScript function that converts centimeters to meters.
```
function cmToM(cm) {
    Return cm / 100;
}

Var meters = cmToM(100);
```

The code above takes a number of centimeters as input and returns the equivalent number of meters. The code ``var meters = cmToM(100)`` is used to invoke the function.

### JAVASCRIPT FILE NAMING CONVENTION
- Function names: when naming functions, start with a verb that describes the action the function performs. Also, be consistent with the verbs you used for the same action to ensure code readability.

- Class and file names: PascalCase and kebab-case are typically used in JavaScript naming as they are more readable and easier to type. The first letter of each word when using PascalCase is capitalized e.g HomePage.js. while for kebab case, each word is separated with a hyphen. E.g home-page.js

- Be specific with names: Giving your variables more specific names will make your code easier to read and understand. It will also reduce the need to overpopulate your code with comments which in retrospect, is part of JavaScript best practice.

- Variable names: It should be self-explanatory and descriptive of the variable’s purpose so that it is easy for you to understand the function it performs without having to read comments.

## JAVASCRIPT DOM
The Document Object Model (DOM) is a programming interface that treats HTML (HyperText Markup Language) and XML (Extensible Markup Language) documents as a logical tree structure connecting web pages to scripts or programming languages. DOM lets us easily access and manipulate tags, IDs, classes, attributes, or elements of HTML using the command line provided by the document object.

We will try to understand what the Document Object Model (DOM) is with the example below using an HTML file:
```
<Table>
    <Rows>
        <TR>
            <TD> ReactJs </TD>
            <TD> VueJs </TD>
        </TR>
        <TR>
            <TD> AngularJs </TD>
            <TD> SvelteJs </TD>
        </TR>
    </Rows>
</Table>
```
The Document Object Model for the HTML above is represented with the table below:
![Document Object Model table](/assets/DOM.png) 

### SELECTING THE HTML ELEMENT IN THE DOM
There are several ways to select elements in the DOM, some of which are.
- getElementsByTagName: selects all elements with a specified tag name.
- getElementsByClassName: Selects all elements with a specified class name.
- getElementById: selects an element by its id attribute.
- querySelectorAll: selects all elements that match a specified CSS selector.
- querySelector: selects the first element that matches a specified CSS selector.
- createElement: creates a new element with the specified tag name.
- appendChild: adds a new child element to the end of a parent element.
- removeChild: removes a child element from a parent element.

### MANIPULATING HTML ELEMENTS IN THE DOM
After you have successfully selected an HTML element in the DOM using one of the methods above, you can manipulate it in the following ways using JavaScript.
- Add or remove attributes: use `setAttribute` and `removeAttribute` to perform this function.
- Create and add a new element: Use the `createElement` and `appendChild` methods to create new elements and add them as children of an existing element.
- How to set innerHTML: Use the `.innerHTML()` property to add its text node.
- How to insert one Element before another: use the `insertBefore()` property that accepts two parameters, the newNode and the `existingNode` in this order, `document.insertBefore(newNode, existingNode)`.
- How to replace a child Element: You are going to use the `replaceChild()` JavaScript method which accepts two parameters, the `newNode` and the `existingNode` in this order. `document.replaceChild(newNode, existingNode)`.
- How to toggle a Class in CSS: Use the `classList.toggle()` JavaScript function.

## JAVASCRIPT LIBRARIES
JavaScript libraries came as a result of JavaScript communities recognizing that certain patterns in the code were being used repeatedly to accomplish the same task. This re-writing of the code and also noting that some JavaScript functions need to be implemented multiple times in a project led to the development of JavaScript libraries and frameworks.

### POPULAR JAVASCRIPT LIBRARIES
- ReactJs

- Lodash

- JQuery

- Anime.js

- D3.js

### WHAT ARE JAVASCRIPT FRAMEWORKS
JavaScript frameworks are collections of pre-written codes that help developers shape and organize the structure for building web applications. A subtle difference between JavaScript frameworks and libraries is that while JavaScript frameworks provide you with all the necessary tools (templates) you could need on a web application, JavaScript libraries are pieces of code we pick up and use in our project.

Summarily JavaScript libraries are pieces of code that add style and function to an already constructed application while JavaScript frameworks are templates you use to build the application itself.

### POPULAR JAVASCRIPT FRAMEWORKS
- AngularJs

- VueJs

- NodeJs

- EmberJs

- NuxtJs

- NextJs

## CONCLUSION
We’ve come to the end of this article, and I want to believe you found this article helpful. JavaScript forms the bedrock of you being a top-notch developer as it is a stepping stone to learning other languages of the web. We have been able to understand what JavaScript is, its fundamentals, how the DOM works, its frameworks, and libraries. I want to keep practicing, showing up daily, and you will understand it very well in no time.

### RESOURCES FOR LEARNING JAVASCRIPT
- [W3Schools JavaScript tutorials](https://w3schols.com/js/)
- [Freecodecamp](https://freecodecamp.org/learn/javascript-algorithms-and=data-structures/)
- [Microsoft Channel 9: JavaScript fundamentals and development for absolute beginners](https://learn.microsoft.com/en-us/shows/javascript-fundamentals-development-for-absolute-beginers/)
- [MDN JavaScript](htttps://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [Learn JavaScript](https://learnjavascript.onlne)
- [Scrimba learn React for free](https://scrimba.com/learn/learnreact)
- [A better way to learn Angular](https://thinkster.io/topics/angular2)