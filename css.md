# My learning about CSS
The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

One could use external and internal css. 

`<link>`
The `<link>` element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an
empty element (meaning it does not need a closing tag), and it lives inside the `<head>` element.
It should use three attributes:
`href`
This specifies the path to the CSS file (which is often placed in a folder called css or styles).
`type`
This attribute specifies the type of document being linked to. The value should be text/css.
`rel`
This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file

`<style>`
You can also include CSS rules within an HTML page by placing them inside a `<style>` element, which usually sits inside the `<head>` element of the page.
The `<style>` element should use the type attribute to indicate that the styles are specified in CSS. The value should be text/css.
When building a site with more than one page, you should use an external CSS style sheet. This: 
- Allows all pages to use the same style rules (rather than repeating them in each page).
- Keeps the content separate from how the page looks.
- Means you can change the styles used across all pages by altering just one file (rather than each individual page).