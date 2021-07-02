## EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS:

![chart](https://th.bing.com/th/id/OIP.6lF2e_un-gb-HkA42hRL_wHaHc?pid=ImgDet&rs=1)

* Charts are  better for displaying data visually than tables .it has the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

![chart](https://th.bing.com/th/id/OIP.c47mUid25EEabHw0ieWHgwHaDn?pid=ImgDet&rs=1)

* to get started with charts we use  Chart.js.
* The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script
* To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart
* Next, we need to write a script that will retrieve the context of the canvas

* Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart.

## Basic usage of canvas:

* At first sight a `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes.

* the `<canvas>` element has only two attributes, width and height.

* The id attribute isn't specific to the `<canvas> `element but is one of the global HTML attributes which can be applied to any HTML element (like class for instance).


* The `<canvas>` element can be styled just like any normal image (margin, border, background…).

![canvas](https://th.bing.com/th/id/R.951eb85471e3e7136b27d94cbe0b7698?rik=znWX6wltfA%2f53A&pid=ImgRaw)

**Drawing shapes with canvas**:

* Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y).

**Rectangular shape:**

* There are three functions that draw rectangles on the canvas:

1. fillRect(x, y, width, height)
**Draws a filled rectangle.**
2. strokeRect(x, y, width, height)
**Draws a rectangular outline.**
3. clearRect(x, y, width, height)
**Clears the specified rectangular area, making it fully transparent.**

**Drawing paths**:
1. you create the path.
2. you use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.

**Applying styles and colors**:
* If we want to apply colors to a shape, there are two important properties we can use:
**fillStyle and strokeStyle**.

## Drawing text:

*The canvas rendering context provides two methods to render text:

1. fillText(text, x, y [, maxWidth])
**Fills a given text at the given (x,y) position.
 Optionally with a maximum width to draw.**
 
2. strokeText(text, x, y [, maxWidth])
**Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.**

