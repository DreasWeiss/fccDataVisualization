# Use a Pre-Defined Scale to Place Elements
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/use-a-pre-defined-scale-to-place-elements) [solution](./solution.html)
<br>
With the scales set up, it's time to map the scatter plot again. The scales are like processing functions that turn the x and y raw data into values that fit and render correctly on the SVG. They keep the data within the screen's plotting area.

You set the coordinate attribute values for an SVG shape with the scaling function. This includes x and y attributes for rect or text elements, or cx and cy for circles. Here's an example:
```
shape
  .attr("x", (d) => xScale(d[0]))
```
Scales set shape coordinate attributes to place the data points onto the SVG. You don't need to apply scales when you display the actual data value, for example, in the text() method for a tooltip or label.
Use xScale and yScale to position both the circle and text shapes onto the SVG. For the circles, apply the scales to set the cx and cy attributes. Give them a radius of 5 units, too.

For the text elements, apply the scales to set the x and y attributes. The labels should be offset to the right of the dots. To do this, add 10 units to the x data value before passing it to the xScale.

## Tests
Waiting: Your code should have 10 circle elements.
Waiting: The first circle element should have a cx value of approximately 91 and a cy value of approximately 368 after applying the scales. It should also have an r value of 5.
Waiting: The second circle element should have a cx value of approximately 159 and a cy value of approximately 181 after applying the scales. It should also have an r value of 5.
Waiting: The third circle element should have a cx value of approximately 340 and a cy value of approximately 329 after applying the scales. It should also have an r value of 5.
Waiting: The fourth circle element should have a cx value of approximately 131 and a cy value of approximately 60 after applying the scales. It should also have an r value of 5.
Waiting: The fifth circle element should have a cx value of approximately 440 and a cy value of approximately 237 after applying the scales. It should also have an r value of 5.
Waiting: The sixth circle element should have a cx value of approximately 271 and a cy value of approximately 306 after applying the scales. It should also have an r value of 5.
Waiting: The seventh circle element should have a cx value of approximately 361 and a cy value of approximately 351 after applying the scales. It should also have an r value of 5.
Waiting: The eighth circle element should have a cx value of approximately 261 and a cy value of approximately 132 after applying the scales. It should also have an r value of 5.
Waiting: The ninth circle element should have a cx value of approximately 131 and a cy value of approximately 144 after applying the scales. It should also have an r value of 5.
Waiting: The tenth circle element should have a cx value of approximately 79 and a cy value of approximately 326 after applying the scales. It should also have an r value of 5.
Waiting: Your code should have 10 text elements.
Waiting: The first label should have an x value of approximately 100 and a y value of approximately 368 after applying the scales.
Waiting: The second label should have an x value of approximately 168 and a y value of approximately 181 after applying the scales.
Waiting: The third label should have an x value of approximately 350 and a y value of approximately 329 after applying the scales.
Waiting: The fourth label should have an x value of approximately 141 and a y value of approximately 60 after applying the scales.
Waiting: The fifth label should have an x value of approximately 449 and a y value of approximately 237 after applying the scales.
Waiting: The sixth label should have an x value of approximately 280 and a y value of approximately 306 after applying the scales.
Waiting: The seventh label should have an x value of approximately 370 and a y value of approximately 351 after applying the scales.
Waiting: The eighth label should have an x value of approximately 270 and a y value of approximately 132 after applying the scales.
Waiting: The ninth label should have an x value of approximately 140 and a y value of approximately 144 after applying the scales.
Waiting: The tenth label should have an x value of approximately 88 and a y value of approximately 326 after applying the scales.