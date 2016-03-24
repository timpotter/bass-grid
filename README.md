Bass Grid v1.3
==============

### A smart, lightweight Flexbox grid, built with Sass.

## This version is currently in development. Feel free to use it and post any issues you encounter

Bass uses the power of Sass to create and calculate flexible column widths and layouts based on the following customisable variables.

```
$base-width: 100%; 				// Best to leave this at 100%

$columns: 12; 					// Number of columns. 12 is used as default it's easily divisible, but you could also have 16, 24 etc

$base: $base-width/$columns; 	// Calculates single column width - 100% / 12 = 8.33333%

$gutter: 2%; 					// Space between columns (Must be a percentage)

$breakpoint: 640px; 			// Point to snap to single column layout

$container-width: 960px; 		// Sets the width of the container if needed

```
Want to change the number of columns or the breakpoint? Simply amend these values and using a Sass [pre-processor](http://sass-lang.com/install), compile `bass-grid.scss:bass-grid.css`.
