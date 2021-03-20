# Problem Domain, Objects, and the DOM

## Problem Domain

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

1. Make the problem domain easier
2. Get better at understanding the problem domain

You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.

## Object Literals

Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

- IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES.
- IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS.

## Document Object Model (DOM)

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas:

- MAKING A MODEL OF THE HTM L PAGE.
- ACCESSING AND CHANGING THE HTML PAGE.

- The browser represents the page using a DOM tree.
- DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
- You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.
- Whenever a DOM query can return more than one node, it will always return a Nadel i st.
- From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.
-An element node can contain multiple text nodes and child elements that are siblings of each other.
- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).
- Browsers offer tools for viewing the DOM tree .