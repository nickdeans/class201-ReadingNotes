# HTML Links, JS Functions, and Intro to CSS Layout

## Links

**Links** - Are the defining feature of the web because they allow you to move from one page to another. Enabling the very idea of browsing or surfing.

Links are created using the "a" element. Users can click on anything between the opening tag and closing.

```
<a href="https://www.imdb.com>IMDB</a>
```

### Email Links

To create a link that starts up the user's email program and adresses an email to a specified email address, you can use the "a" element but make sure to incorporate the href attribute starting with mailto: then follow it with the email.

```
<a href="mailto:jon@example.com">Email Jon</a>
```

## Layout

### Buildding Blocks

CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

1. **Block-Level Element** - Start on a new line
2. **Inline Element** - Flow in bewtween surrounding text.

## Controlling the Position of Elements

CSS has the following **position schemes** that allow you to control the layout of a page.

- **Normal Flow** - Every block-level element appears on a new line, cauasing each item to appear lower down the page than the previous one. It will always revert to default behavior and leave spaces bewteen each elemet regardless of specifying a width.
- **Relative Positioning** - This moves an element from the position it would be in normal flow, shifting it in any direction you would like it to go.
- **Absolute Positioning** - This positions the element in relation to its containing element. It does not affect the position of any surrounding elements. These elements move as users scroll up and down the page.

**Floating Elements** - Floating an element allows you to take that element out of normal flow and position it to the left or right.

## Layouts

1. Fixed width layouts - Fixed width layout designs do not change size as the user increasesor descreases the size of their browser window.
2. Liquid Layouts - Liquid layout designs stretch and contrast as the user increases or decreases the size of their browser window. They tend to use percentages.

**Grids** - Help creates professional and felxible designs. - Designers keep pages within the 960-1000 pixels wide and indicate what the site is about within the top 600 pixels.

**CSS Framework** - Provides rules for common tasks.

## Functions, Methods, and Objects

**Functions** - Functions consist of a series of statements that have been grouped together because they perform a specifiv task.

**Methods** - A Method is the same as a function, except methods are created inside(and are part of) an onject.

**Objects** - Objects are made up of properties and methods.
