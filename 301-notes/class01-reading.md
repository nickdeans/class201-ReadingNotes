# SMACSS and Responsive Web Design

## Responsive Web Design
- The practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.

Responsive web design is broken into three main components, incuding flexible layouts, media queries, and flexible media.
1. Flexible Layouts - the practice of building the layout of a website grid, capable of dynamically resizing to any width.
- Flexible Grid is used to be adaptable to any screen. It does not used fixed points such as pixels but instead uses relative units such as percentages. EX Below:

```
section,
aside {
  margin: 1.858736059%; /*  10px ÷ 538px = .018587361 */
}
section {
  float: left;
  width: 63.197026%;    /* 340px ÷ 538px = .63197026 */   
}
aside {
  float: right;
  width: 29.3680297%;  /* 158px ÷ 538px = .293680297 */
}
```

2. Media Queries - were built as an extension to media types commonly found when targeting and including styles. 
- There are a couple ways to use media queries, using the @media rule inside of an existing style sheet, importing a new style sheet using the @import rule, or by linking to a seperate style sheet from within the HTML document. EX Below:

```
/* @media Rule */
@media all and (max-width: 1024px) {...}

/* @import Rule */
@import url(styles.css) all and (max-width: 1024px) {...}
```

3. Flexible Media - as viewports begin to change size media doesn't always follow suit. Images, videos, and other media types need to be scalable, changing their size as the size of the viewport changes.
- One quick way to make media scalable is by using the max-width property with a value of 100%. Doing so ensures that as the viewpoint gets smallers any media will scale down according to its containers width. EX Below:

```
img, video, canvas {
  max-width: 100%;
}
```

## Float
**Float** is a CSS positioning property. Images may be set into the oage such that text wraps around them as needed.

What are floats used for?
- Floats can be used to create entire web layouts. 

Clearing the Float 
- Float's siter property is "clear". An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float. 