# JS Object Literals; The DOM

## Objects 
**Objects** - Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.
**Property** - If a variable is part of an object it is called a propety. 
**Method** - If a function is part of an object it is called a method.

## Document Object Model
The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

DOM is neither part of the HTML, nor part of JS; It is seperate of rules.

**DOM Tree** - The DOM specifies the way in which the browser should structure the model which is called a DOM Tree

The DOM is called an object model because it is made of Objects.

### Working with the DOM Tree
Accessing and updating the DOM involves two steps
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.

**DOM Queries** - Methods theat find elements in the DOM tree are called DOM Queries.

**Node List** - If a method can return more than one node, it will
always return a Node list.

Methods that return a single element node.
    - getElementByld('id')
    - querySelector('css selector')

Methods that return one or more elements as a Node List.
    - getElementsByClassName('class')
    - getElementsByTagName('tagname')
    - querySelectorAll('css selector')


) 