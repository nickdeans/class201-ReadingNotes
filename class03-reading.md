# Flexbox and Templating

## JavaScript Templating 
A fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. 

**Mustache** - is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.

mustache.js is an implementation of the mustache template system in JavaScript. It is often considered the base for JavaScript templating. And, since mustache supports various languages, we don’t need a separate templating system on the server side. See EXAMPLE BELOW

```
Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn
```

Above the two braces {{name}} is mustache syntax to show that it is a placeholder. When mustache compiles this it will look for the 'name' property in the object we pass it in and replace {{name}} with the actual value, e.g. "Sherlynn"

**Mustache Express** - If you intend to use mustache with node and express, you can use mustahce express. You must install it in your terminal and configure mustache-express in your server.

```
HTML
<h1>Hello {{name}}</h1>
```
```
res.render('hello', {"name": "Sherlynn"})
```
```
var nameObject = {"name": "Sherlynn"}
res.render('hello', nameObject)
```

In this example you can see the first parameter ‘hello’ refers to the hello.html file (no need to include the extension (e.g. hello.html) as it has been previously set as html.

The second parameter would be the JSON data itself. We can also pass in a variable representing the data, for example:


## Flexbox
The Flexbox layout aims to provide a more efficient way to lay out, align and distribute space among items in a container, even when there size is unknown and/or dynamic.

The main idea behind the flex layout is to give the container the ability to alter its items’ width/height (and order) to best fill the available space (mostly to accommodate to all kind of display devices and screen sizes). 

### Properties for the Parent (flex container)
**display** - This define a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.

```
.container {
  display: flex; /* or inline-flex */
}
```

**flex-direction** - This establishes the main-axis, thus defining the direction flex items are places in the flex container.

```
.container {
  flex-direction: row | row-reverse | column | column-reverse;
}
```

**flex-wrap** - By default, flex items will all try to fit onto one line. You can change that and allow the items to wrap as needed with this property.

```
.container {
  flex-wrap: nowrap | wrap | wrap-reverse;
}
```

**justify-content** - This defines the alignment along the main axis. It helps distribute extra free space leftover when either all the flex items on a line are inflexible, or are flexible but have reached their maximum size.

```
.container {
  justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right ... + safe | unsafe;
}
```

**align-items** - This defines the default behavior for how flex items are laid out along the cross axis on the current line. Think of it as the justify-content version for the cross-axis (perpendicular to the main-axis).

```
.container {
  align-items: stretch | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end + ... safe | unsafe;
}
```

**align-content** - This aligns a flex container’s lines within when there is extra space in the cross-axis, similar to how justify-content aligns individual items within the main-axis.

```
.container {
  align-content: flex-start | flex-end | center | space-between | space-around | space-evenly | stretch | start | end | baseline | first baseline | last baseline + ... safe | unsafe;
}
```