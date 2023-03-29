# Learn About SVG in D3
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/learn-about-svg-in-d3) [solution](./solution.html)
<br>
SVG stands for Scalable Vector Graphics.

Here "scalable" means that, if you zoom in or out on an object, it would not appear pixelated. It scales with the display system, whether it's on a small mobile screen or a large TV monitor.

SVG is used to make common geometric shapes. Since D3 maps data into a visual representation, it uses SVG to create the shapes for the visualization. SVG shapes for a web page must go within an HTML svg tag.

CSS can be scalable when styles use relative units (such as vh, vw, or percentages), but using SVG is more flexible to build data visualizations.
Add an svg node to the body using append(). Give it a width attribute set to the provided w constant and a height attribute set to the provided h constant using the attr() or style() methods for each. You'll see it in the output because there's a background-color of pink applied to it in the style tag.

Note: When using attr() width and height attributes do not have units. This is the building block of scaling - the element will always have a 5:1 width to height ratio, no matter what the zoom level is.

## Tests
Your document should have 1 svg element.
Waiting: The svg element should have a width attribute set to 500 or styled to have a width of 500px.
Waiting: The svg element should have a height attribute set to 100 or styled to have a height of 100px.