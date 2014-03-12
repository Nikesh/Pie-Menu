# Simple configurable Pie Menu

Use this Pie Menu in your projects, it's simple and fully customizable!

## Usage

Just link query.menu.js on your html document and Use html structure like bellow:

```html
  <div id='outer_container' class="outer_container" >
		<a class="menu_button" href="#" title="Toggle"><span>Menu Toggle</span></a>
		<ul class="menu_option">
		  <li><a href="#"><span>Item</span></a></li>
		  <li><a href="#"><span>Item</span></a></li>
		  <li><a href="#"><span>Item</span></a></li>
		  <li><a href="#"><span>Item</span></a></li>
		  <li><a href="#"><span>Item</span></a></li>
		</ul>
	</div>
```

JavaScript
```html
	$('#outer_container').PieMenu({
		'starting_angel':0(Starting Angle in degree),
		'angel_difference' : 90(Displacement angle in degree),
		'radius':100 (circle radius in px),
	});	
```
[Live demo!](http://nikesh.github.com/Pie-Menu)

# MIT License

Copyright (C) 2013 Nikesh Hayaran

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
