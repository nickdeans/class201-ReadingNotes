# Tables 

The "Table" tag defines nd HTMLtable. Each table row is defined with a "tr" tag. Each table header is defined with a "th" tag. Each table/cell is defined with a "td" tag. By default the text within the "td" tag are regular and left aligned. By default the text within the "th" tag are bold and centered.
```
<table>
<tr>
<td>
<th>
```

To add a border to a table, use the CSS border property:
```
table, th, td {
    border: 1px solid black;
}
```

Cell padding specifies the space between the content and the border. To set padding use the css padding property:
```
th, td {
    padding: 15px;
}
```

# Functions, Methods, and Objects 
How to create an Object:
    1. Create the object
    2. Add the properties 
    3. Add the Method

The Keyword "This" is commonly used inside of functions and objects. Where the function is declared alters what "this" means. It always refers to one object, sually the object in which the function operates. 

**Global scope/context** - When a function is created at the top level of a script. 

**Method** - When a function is defined inside an object it becomes a method.

**Variables** - A varibale has just one key(the variable name) and one value.

**Arrays** - Arrays can store multiple pieces of information. 

You can combine arrays and objects to create to create complex data structures. Arrays can also store a series of objects(and remember their order). Objects can also hold arrays(as values of their properties).