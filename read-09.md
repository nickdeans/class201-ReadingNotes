# Forms and JS Events 

## Forms
HTML borrows the idea of a form to refer to different elements that allow you to collect information from visitors to your site. 

The best known form on the web is probably the search box that sits right in the middle of Google's homepage.

### Several Types of Form Control
- **Adding Text**:
    - Text input uses a single line of text. Examples include email lines, names, passwords, messages, comments.
- **Making Choices**:
    - Examples include radio buttons, checkboxes, and drop-down boxes.
- **Submitting Forms**:
    - Submit buttons to submit data from your form to another web page. These also include image buttons and subscription buttons.
- **Uploading Files**:
    - File uploads allow users to upload files including images to a website.

### Form Structure
Form controls live inside a "form" element. This element should always carry the action attribute and will usually have a method and id attribute too.
```<form action="https://example.com" method="get" id=>
        <p>This is where the form control will appear.</p>
    </form>
```

### Types of Input
The "input" element is used to create several different form controls. The value of the ype of attribute determines what kind of input they will be creating. 
- type="text" is when the attribute has a value of text. Creates a single line text input.
- the name attribute is used to tell the server which form control each piece of data was entered in to.
- the size attribute should not be used on new forms but was used to indicate the width of the text.
- the maxlength attribute limits the number of characters a user may enter.
- type="password" is when the attribute text has a value of password which creates a text box that is blocked out so the user can enter their password.
- the "textarea" element is used to creat a multi-line text input for paragraphs and does not need a closing tag.
- type="radio" is used to create radio buttons within the input tag.
- type="checkbox" is used to creat a checkbox in the input tag.
- type="submit" is used to create a submit button.

Whenever you want to collect information from visitors you will need a form, which lives inside a "form" element.

### Lists, Tables, and Forms

**Bullet Point Styles** - The list-style-type property allows you yo control the shape or style of a bullet point(also known as a marker).

Forms are easier to use if the form controls are vertically aligned using css.

### Events
When you browse the web, your browser registers different type of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events. 

**How Events Trigger JavaScript Code**
    1. Select Element
    2. Specify Event
    3. Call Code