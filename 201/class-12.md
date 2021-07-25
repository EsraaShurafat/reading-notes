# CHART.JS
![CHART.JS](https://www.bypeople.com/wp-content/uploads/2020/02/javascript-chart-js.png)
- Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.
## Drawing a line chart
- To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. 
## Drawing a bar chart
- Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element
## Creating a Chart
- It's easy to get started with Chart.js. All that's required is the script included in your page along with a single canvas node to render the chart.
[Read this article on the Chart.js API.](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

[https://www.chartjs.org/docs/latest/](https://www.chartjs.org/docs/latest/)
# Basic usage of canvas
- Note: If your renderings seem distorted, try specifying your width and height attributes explicitly in the canvas attributes, and not using CSS.
## Fallback content
- The canvas element differs from an img tag in that, like for video, audio, or picture elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.
## Checking for support
- The fallback content is displayed in browsers which do not support <canvas>. Scripts can also check for support programmatically by testing for the presence of the getContext.
### Note: it is not good practice to embed a script inside HTML. We do it here to keep the example concise.
[https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

## Drawing shapes with canvas
- The grid
Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high.
- Drawing rectangles
Unlike SVG, canvas only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.
## Drawing paths
- Now let's look at paths. A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths.
### Note: 
- When the current path is empty, such as immediately after calling beginPath, or on a newly created canvas, the first path construction command is always treated as a moveTo, regardless of what it actually is. For that reason, you will almost always want to specifically set your starting position after resetting a path.
-  When you call fill, any open shapes are closed automatically, so you don't have to call closePath. This is not the case when you call stroke.
- To learn more about the arc function, see the Arcs section below.
- Angles in the arc function are measured in radians, not degrees. To convert degrees to radians .
-  This example requires a slightly larger canvas than the others on this page: 150 x 200 pixels
## Making combinations
- So far, each example on this page has used only one type of path function per shape. However, there's no limitation to the number or types of paths you can use to create a shape. So in this final example, let's combine all of the path functions to make a set of very famous game characters.
[https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

### read these [https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text) 
[https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
