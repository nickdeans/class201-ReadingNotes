# EJS Partials 
Partials are great when you resuse the same HTML across several views. They can be thought as functions that make large website easier to maintain because you don't have to change a piece of text in every page. Instead you can define the reusable code in a file and use it wherever you need.

- First you must create a partial folder under the views folder.
- Create a file that will hold only the html for the pages you will use it on.
- After defining the partials with your html you can now use them in your ejs file templates.
- To include a partial in EJS you use the <%- include(partial_file) %>
- Partials are a simple and easy way to get your text across many different pages by using one page and ejs templating.
