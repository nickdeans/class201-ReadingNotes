# Chart.js, Canvas

Cahrts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.

**Chart.js** - a JavaScript plugin that uses HTML5's canvas element to draw the graph onto the page. It's a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

## Setting up
- The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you will be working in. Then create a new html page and import the script.

```
<html>
    <head>
        <script src='Chart.min.js'><script/>
    </head>
</html>
```

### Drawing a line Chart
- To draw a line chart, the first thing we need to do is create a canvas element in our HTML in whihc Chart.js can draw our chart.

```
<canvas id="buyer" width="600" height="400"></canvas>
```

- Next, we need to write a script that will recieve the context of the canvas, so add this to the foot of your body element:

```
<script>
    var buyer = document.getElementById('buyer').getContext('2d
    new Chart(buyer).Line(buyerData)
</script>
```

Inside the same script tags we need to create our data, in this instance it's an object that contains labels for the base of our chart and datasets to descrie the values on the chart. Add this immediately above the line that begins 'var buyer=':

```
var buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}
```

## Basic Usage of Canvas
The "Canvas" element - At first sight the "canvas" element looks like the "img" element, with the only clear difference being that it doesn't have the src and alt attributes.

### Drawing SHapes with Canvas
Canvas has a grid or coordinate space which you can adjust accordingly.

**Drawing Rectangles** - canvas only supports two primitive shapes: rectanlges and paths(lists of points connected by lines)

There are three functions that draw rectangles on the canvas.

```
fillRect(x, y, width, height)
    - Draws a filled rectangle

strokeRect(x,y, width, height)
    - Draws a rectangular outline.

clearRect(x, y, width, height)
    - Clears the specified rectangular area, amking it fully transparent.
```

**Drawing Paths** - A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. 

```
beginPath()
    - Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
Path methods
    - Methods to set different paths for objects.
closePath()
    - Adds a straight line to the path, going to the start of the current sub-path.
stroke()
    - Draws the shape by stroking its outline.
fill()
    - Draws a solid shape by filling the path's content area
```

