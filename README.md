# Cat-and-Light-Project

DOM and Event Fundamentals | Cheat Sheet
1. JavaScript Variables
1.1 Variable Declaration
Variables are like containers for storing values. We can create a variable using the let keyword.

JAVASCRIPT
1.2 Assigning a Value to the Variable
We can put data into a variable using an assignment operator (=).


JAVASCRIPT
Try out changing the JavaScript Variables and their Values in the below Code Playground and check the output in the console.



Note
Printing a variable without assigning a value will give the output undefined.
2. Document Object Model (DOM)
The DOM is the structured representation of the HTML document created by the browser. It allows JavaScript to manipulate, structure, and style your website.

HTML
2.1 Document Object
It is the entry point of the DOM. For accessing any HTML Element, you should always start with accessing the document object first.

2.2 HTML DOM Tree
The DOM tree represents an HTML document as nodes. Each node is referred to as an Object.

dom-tree
2.3 Methods
2.3.1 getElementById
The getElementById() method helps to select the HTML Element with a specific ID.

JAVASCRIPT
2.4 Properties
2.4.1 textContent
To manipulate the text within the HTML Element, we use textContent Property.

2.4.2 style
The style property is used to get or set a specific style of an HTML Element using different CSS properties.

Use Camel Case naming convention (starting letter of each word should be in the upper case except for the first word) for naming the Style Object Properties.

For example, color, fontFamily, backgroundColor, etc.

2.5 Events
Events are the actions by which the user or browser interacts with the HTML Elements. Actions can be anything like clicking a button, pressing keyboard keys, scrolling the page, etc.

2.5.1 onclick Event
The onclick event occurs when the user clicks on an HTML Element. We will give the name of the function as a value for the HTML onclick attribute.
