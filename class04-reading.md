# Responsive Web Design and Regular Expressions

## CSS Grid
The CSS grid layout is used for a grid-based layout system, with rows and columns making it easier to design websites without using floats and positioning.

```
example {
    display: grid;
}
```

By using grid-column-start you are able to move a box anywhere on the grid using rows, columns, and start and end spaces. Each space on a grid is given a position.

```
#example {
    grid-column-start: 3;
}
```

By using the span keyword you can define where you would like the box to span to form the start or end.

```
example {
    grid-column-start: 2;
    grid-column-end: span;
}
```

