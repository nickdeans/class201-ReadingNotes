# CSS Tranforms, Transitions, and Animations
General layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the **transform property**.

### Transform Syntax
 - The syntax for the transform property is simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.

 ```
 div {
     -webskit-transform: scale(1.5);
     -moz-transfrom: scale(1.5);
     transform: scale(1.5);
 }
```

**Transform Origin** - This property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.

**Transitions** - for a transition to take place, an element must have a change in state, and different styles must be identified for each state.

```
.box {
    background: #23hu3u;
    transition-property: background;
    transition-duration: 1s;
    transition-timing-function: linear;
}

.box: hover {
    background: #ff23h27
}
```

### Transitions you can use

**Fade In**

```
.fade {
    opacity:0.5;
}
.fade:hover {
    opacity:1;
}
```

**Change Color**

```
.color:hover {
    background: #34uh2u;
}
```

**Square to Circle**

```
.circle:hover {
    border-radius:50%;
}
```

# What Google Learned About Teams


