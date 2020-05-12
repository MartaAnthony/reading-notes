## Docs for the HTML <canvas> Element & Chart.js

**Chart.js** - JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page: bar charts, line charts, pie charts     
Chart.js documentation: https://www.chartjs.org/docs/latest/.  

`<canvas>`.  
- 2 attributes: width and height (optional)  
- if not set, the size will be 300px wide and 150px high  
- *fallback content* = alternate content for older browsers that you put in `<canvas>` element 
- requires closing tag 
- creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown  
- only supports two primitive shapes: rectangles and paths   

`var canvas = document.getElementById('tutorial');    
var ctx = canvas.getContext(‘2d’);`

*Shapes*  
`fillRect(x, y, width, height)`
Draws a filled rectangle.   
`strokeRect(x, y, width, height)`
Draws a rectangular outline.   
`clearRect(x, y, width, height)`
Clears the specified rectangular area, making it fully transparent.   

`beginPath()`  
`closePath()`  
`stroke()`   
`fill()`   
`moveTo(x, y)`   
`lineTo(x, y)`   
`arc(x, y, radius, startAngle, endAngle, anticlockwise)`     
`arcTo(x1, y1, x2, y2, radius)`   
`quadratiCurveTo()`   
`bezierCurveTo()`  

You can make Pacman in Javascript!     

The `Path2D()` constructor returns a newly instantiated Path2D object.    




