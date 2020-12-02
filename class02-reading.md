# jQuery, Events, and the DOM

## jQuery
Offers a simple way to achieve a variety of common JavaScript tasks quickly and consistently, across all major browsers and without any fallback code needed. It helps perfomr three tasks efficiently, 

1. Select Elements - It is simpler to access
elements using jQuery's CSS-style selectors than it is using DOM queries. The selectors are also more powerful and flexible.


2. Perform Tasks - jQuery's methods let you
update the DOM tree, animate elements into and out of view, and loop through a set of elements, all in one line of code.

3. Handle Events - jQuery includes methods that allow you to attach event listeners to selected elements without having to write any tailback code to support older browsers.

**jQuery** is a JavaScript file that you include in your web pages. It lets you find elements using CSS-style selectors and then do something with the elements using jQuery methods. 

1. Find Elements Using CSS-Style Selectors - a function called jQuery() lets you find one or more elements in the page. It creates an object called jQuery which holds references to those elements. $() is often used as a shorthand to save typing as shown below.

```
$('li.hot)
```

This example has only one paramter: a CSS-style selector. This selector finds all of the <li> elements.

2. Do Something With The Elements Using jQuery Methods - In the example below, a jQuery object is created byt the jQuery() function. The object and the elements it contains is referred to as a matched set or a jQuery selection. You can then use the methods of the jQuery object to update the elements that it contains. Here, the method adds a new value to the class attribute.

```
$('li.hot').addClass('complete');
```

## Looping 
In plain JavaScript, if you wanted to do the same thing to several elements, you would need to write code to loop through all of the elements you selected. 

With jQuery, when a selector returns multiple elements, you can update all of them using the one method. There is no need to use a loop.

In this code, the same value is added to the cl ass attribute for all of the elements that are found using the selector. It doesn't matter if there are one or many.

```
$('li em').addClass('seasonal');
$( ' li .hot') .addClass('favorite');
```

The first line of code the selector applies to only one element and give the class attribute a new value. The second selector applies to several other elemetns to give the class attribute new values as well.

