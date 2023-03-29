# Change the Presentation of a Bar Chart
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/change-the-presentation-of-a-bar-chart) [solution](./solution.html)
<br>
The last challenge created a bar chart, but there are a couple of formatting changes that could improve it:

Add space between each bar to visually separate them, which is done by adding a margin to the CSS for the bar class
Increase the height of the bars to better show the difference in values, which is done by multiplying the value by a number to scale the height
First, add a margin of 2px to the bar class in the style tag. Next, change the callback function in the style() method so it returns a value 10 times the original data value (plus the px).

Note: Multiplying each data point by the same constant only alters the scale. It's like zooming in, and it doesn't change the meaning of the underlying data.

## Tests
The first div should have a height of 120 pixels and a margin of 2 pixels.
Waiting: The second div should have a height of 310 pixels and a margin of 2 pixels.
Waiting: The third div should have a height of 220 pixels and a margin of 2 pixels.
Waiting: The fourth div should have a height of 170 pixels and a margin of 2 pixels.
Waiting: The fifth div should have a height of 250 pixels and a margin of 2 pixels.
Waiting: The sixth div should have a height of 180 pixels and a margin of 2 pixels.
Waiting: The seventh div should have a height of 290 pixels and a margin of 2 pixels.
Waiting: The eighth div should have a height of 140 pixels and a margin of 2 pixels.
Waiting: The ninth div should have a height of 90 pixels and a margin of 2 pixels.