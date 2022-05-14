<h1>1. CSS Selectors</h1>
CSS Selectors
CSS selectors are used to "find" (or select) the HTML elements you want to style.

We can divide CSS selectors into five categories:<br>

Simple selectors (select elements based on name, id, class)<br>
Combinator selectors (select elements based on a specific relationship between them)<br>
Pseudo-class selectors (select elements based on a certain state)<br>
Pseudo-elements selectors (select and style a part of an element)<br>
Attribute selectors (select elements based on an attribute or attribute value)<br>
<br>
<h3>Simple Selectors</h3>
<br><hr>
The CSS id Selector
The id selector uses the id attribute of an HTML element to select a specific element.
The id of an element is unique within a page, so the id selector is used to select one unique element!
To select an element with a specific id, write a hash (#) character, followed by the id of the element.
<hr>
<br>
The CSS class Selector
The class selector selects HTML elements with a specific class attribute.
To select elements with a specific class, write a period (.) character, followed by the class name.
<hr><br>
The CSS Universal Selector
The universal selector (*) selects all HTML elements on the page.
<hr><br>
The CSS Grouping Selector
The grouping selector selects all the HTML elements with the same style definitions.
Look at the following CSS code (the h1, h2, and p elements have the same style definitions):
It will be better to group the selectors, to minimize the code.
To group selectors, separate each selector with a comma.
<br>
Example<br>
h1, h2, p {<br>
<br>
<img src="Simple_selectors.png" alt="Simple Selectors">
  text-align: center;<br>
  color: red;<br>
}
<hr>
