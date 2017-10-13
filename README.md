# Dragging.js

A lightweight **jQuery plugin** that transforms any HTML block into a darggable block.

## Example

[See demo!](https://vldvel.github.io/Dragging.js/demo/index.html)
[Or try it on codepen] (https://codepen.io/vldvel/project/editor/AOPwPB)

## Quick start

1. Include jQuery:

	```html
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
	```

2. Include Dragging.js:

	```html
	<script src="dist/jquery.Dragging.min.js"></script>
	```

3. Call the Dragging.js:

	```javascript
	$('#element').Dragging();

	// Or with speed
	$('#element').Dragging({
		speed: 300
	});

	// Or with all properties
	$('#element').Dragging({
		speed: 300,
		vertical: true,
		horizontal: true
	});
	```

## Options

* **speed** any number (default 300)
* **vertical** true or false (default true)
* **horizontal** true or false (default true)

## Requires

jQuery v1.6.0+

## Credits

[jQuery Boilerplate](https://jqueryboilerplate.com/)

## License

The MIT License (MIT).
