<h1>3. CSS Insertion</h1>
Three Ways to Insert CSS
There are three ways of inserting a style sheet:

External CSS

Internal CSS

Inline CSS


<h3>External CSS</h3>
With an external style sheet, you can change the look of an entire website by changing just one file!
Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

<h3>Internal CSS</h3>
An internal style sheet may be used if one single HTML page has a unique style.
The internal style is defined inside the <style> element, inside the head section.
  
<h3>Inline CSS</h3>
An inline style may be used to apply a unique style for a single element.
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
  
  
--If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used
