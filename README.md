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
