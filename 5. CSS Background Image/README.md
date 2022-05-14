<h1>5.CSS Background Image</h1>

The background-image property specifies an image to use as the background of an element.
By default, the image is repeated so it covers the entire element.
<hr>

CSS background-repeat
By default, the background-image property repeats an image both horizontally and vertically.
Some images should be repeated only horizontally or vertically, or they will look strange
<hr>
To repeat an image vertically, set background-repeat: repeat-y;

repeated only horizontally background-repeat: repeat-x;
<hr>
CSS background-repeat: no-repeat
Showing the background image only once is also specified by the background-repeat property:
<hr>

CSS background-position
The background-position property is used to specify the position of the background image.
<hr>

CSS background-attachment
The background-attachment property specifies whether the background image should scroll or be fixed (will not scroll with the rest of the page):

Specify that the background image should be fixed:

Specify that the background image should scroll with the rest of the page:
<hr>

CSS background - Shorthand property
To shorten the code, it is also possible to specify all the background properties in one single property. This is called a shorthand property.
<br>
body {<br>
  background: #ffffff url("img_tree.png") no-repeat right top;<br>
}<br>

When using the shorthand property the order of the property values is:
<br>
background-color<br>
background-image<br>
background-repeat<br>
background-attachment<br>
background-position<br>
<br>It does not matter if one of the property values is missing, as long as the other ones are in this order. Note that we do not use the background-attachment property in the examples above, as it does not have a value.

