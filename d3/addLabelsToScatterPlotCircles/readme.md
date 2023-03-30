# Add Labels to Scatter Plot Circles
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/add-labels-to-scatter-plot-circles) [solution](./solution.html)
<br>
You can add text to create labels for the points in a scatter plot.

The goal is to display the comma-separated values for the first (x) and second (y) fields of each item in dataset.

The text nodes need x and y attributes to position it on the SVG. In this challenge, the y value (which determines height) can use the same value that the circle uses for its cy attribute. The x value can be slightly larger than the cx value of the circle, so the label is visible. This will push the label to the right of the plotted point.
Label each point on the scatter plot using the text elements. The text of the label should be the two values separated by a comma and a space. For example, the label for the first point is 34, 78. Set the x attribute so it's 5 units more than the value you used for the cx attribute on the circle. Set the y attribute the same way that's used for the cy value on the circle.

## Tests
Your code should have 10 text elements.
Waiting: The first label should have text of 34, 78, an x value of 39, and a y value of 422.
Waiting: The second label should have text of 109, 280, an x value of 114, and a y value of 220.
Waiting: The third label should have text of 310, 120, an x value of 315, and a y value of 380.
Waiting: The fourth label should have text of 79, 411, an x value of 84, and a y value of 89.
Waiting: The fifth label should have text of 420, 220, an x value of 425, and a y value of 280.
Waiting: The sixth label should have text of 233, 145, an x value of 238, and a y value of 355.
Waiting: The seventh label should have text of 333, 96, an x value of 338, and a y value of 404.
Waiting: The eighth label should have text of 222, 333, an x value of 227, and a y value of 167.
Waiting: The ninth label should have text of 78, 320, an x value of 83, and a y value of 180.
Waiting: The tenth label should have text of 21, 123, an x value of 26, and a y value of 377.