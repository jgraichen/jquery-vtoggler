UJS CheckBox Visibility Toggler
===============================

A jQuery extension thats allows a input check box to show or hide other side 
elements depending on if it is checked or not. It uses unobtrusive JavaScript
via HTML5 compatible attributes. 
 
Example:

	<input type="checkbox" data-vtoggle="#container" />

The check box above toggle the visibility of element "#container". If the 
check box is not checked the container will be hidden.

Second example:

	<input type="checkbox" data-vtoggle-hide="img, .hide-with-images"  />

This check box will hide all IMG-tags and all element with the CSS class
"hide-with-images" when check box is checked.


This plugin can also be used to create own check box handler by using
the checkboxToggle function added to jQuery:

	$(element).checkboxToggle(function(checked) {
	  ...
	});

Another helper can be used to simply set the visibility of an element:

	$(element).setVisibility(true);


License
-------

MIT License. Copyright (C) 2011 Jan Graichen